# CityHoops
{
  "settings": {
    "name": "IT SPACE",
    "currentPage": "index.html",
    "theme": {
      "name": "mobirise4",
      "title": "Mobirise 4",
      "styling": {
        "primaryColor": "#149dcc",
        "secondaryColor": "#ff3366",
        "successColor": "#F7ED4A",
        "infoColor": "#82786E",
        "warningColor": "#879A9F",
        "dangerColor": "#B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4.25,
        "display2Font": "Rubik",
        "display2Size": 3,
        "display5Font": "Rubik",
        "display5Size": 1.5,
        "display7Font": "Rubik",
        "display7Size": 1,
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": true,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": []
    },
    "path": "@PROJECT_PATH@",
    "versionFirst": "4.11.6",
    "siteFonts": [
      {
        "css": "'Rubik', sans-serif",
        "name": "Rubik",
        "url": "https://fonts.googleapis.com/css?family=Rubik:300,300i,400,400i,500,500i,700,700i,900,900i"
      }
    ],
    "favicon": false,
    "noImageResize": true,
    "robotsSwitcher": false,
    "sitemapSwitcher": false,
    "sitemapSwitcherAuto": false,
    "siteUrl": false,
    "cookiesAlert": false,
    "gdpr": false,
    "uniqCompNum": 17,
    "versionPublish": "4.11.6",
    "screenshot": "screenshot.png"
  },
  "pages": {
    "index.html": {
      "settings": {
        "main": true,
        "title": "Home",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "components": [
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"5\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"1\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    SPACE IT</h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showSubTitle\">\n                    BRING YOUR LIFE ONLINE</h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Space IT brings your life online.</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SERVICES</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "sd44xnKnnP",
          "_anchor": "header16-g",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/mbr-1920x1492.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    SMART SPACE</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Connect your commercial or residential building's infrastructure.</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">CONTACT</a> <a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SHOP</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rUEYBsJvgL",
          "_anchor": "header2-3",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SEARCH MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rUEYCpizsv",
          "_anchor": "header16-4",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "-webkit-flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important",
                "-webkit-align-items": "center",
                "-webkit-justify-content": "center"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              "display": "-webkit-inline-flex",
              "align-items": "center",
              "-webkit-align-items": "center",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              }
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "-webkit-align-items": "center",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  },
                  "a": {
                    "display": "inline-flex"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "@media (min-width: 1024px)": {
                "&:not(.navbar-short) .navbar-collapse when (@showLogo)": {
                  "max-height": "~\"calc(98.5vh - @{logoSize}rem)\""
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 1023px)": {
              ".navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0",
                "-webkit-flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto",
              "-webkit-flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#232323\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.co\">\n                         <img src=\"../_images/logo2.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\">\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Space IT</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\">\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-home mbr-iconfont mbr-iconfont-btn\"></span>\n                        Services\n                    </a>\n                </li>\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-search mbr-iconfont mbr-iconfont-btn\"></span>\n                        About Us\n                    </a>\n                </li>\n            </ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\">\n                <a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.co\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a>\n            </div>\n        </div>\n    </nav>\n</section>",
          "_cid": "rUEYRSarcN",
          "_anchor": "menu1-7",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/mbr-1920x1280.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    CONNECTIONS</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Cat6a for 10GB speeds!</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">CONTACT</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SHOP</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rUEYB1m9S1",
          "_anchor": "header2-2",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SEARCH MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rUEYDDNEAK",
          "_anchor": "header16-5",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/mbr-1920x1308.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    MONITORS</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Shop a variety of 4k, 8k, &amp; UHD 32\"-120\" models</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">CONTACT</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SHOP</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rUF1dfxAOe",
          "_anchor": "header2-8",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SEARCH MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rUEYEMLFJz",
          "_anchor": "header16-6",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/mbr-1920x1440.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    PERIPHERALS</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Keyboards, mice, &amp; adapters.</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SHOP</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">CONTACT US!</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rUEYzBRvS4",
          "_anchor": "header2-0",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"2\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">SEARCH MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rUF1eOyYVx",
          "_anchor": "header16-9",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/mbr-1920x1400.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    CUSTOM SPECS</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Request custom build outs for the home or office network infrastructure.</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">CONTACT US!</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rUEYAAZfb3",
          "_anchor": "header2-1",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem",
                "text-align": "center"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".mbr-text": {
              "color": "#767676"
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#000",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "-webkit-flex-wrap": "wrap",
                "flex-wrap": "wrap",
                "-webkit-justify-content": "flex-end",
                "justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#232323"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "-webkit-justify-content": "center",
                  "justify-content": "center"
                }
              }
            }
          },
          "_name": "footer5",
          "_customHTML": "<section group=\"footer5\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline=\"\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"3\">\n        <input type=\"range\" inline=\"\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"3\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked=\"\">\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\">0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\" selected=\"\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax=\"\">\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected=\"\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked=\"\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n        <input type=\"range\" inline=\"\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay &amp;&amp; bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.co/\">\n                       <img src=\"../_images/logo2.png\" alt=\"Mobirise\">\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-md-9\">\n                <p class=\"mbr-text align-right links mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".links\">\n                    <a href=\"#\" class=\"text-black\">ABOUT</a> &nbsp;&nbsp;&nbsp;&nbsp;\n                    <a href=\"#\" class=\"text-black\">TERMS</a> &nbsp;&nbsp;&nbsp;&nbsp;\n                    <a href=\"#\" class=\"text-black\">CAREERS</a> &nbsp;&nbsp;&nbsp;&nbsp;\n                    <a href=\"#\" class=\"text-black\">CONTACT</a>\n                </p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-md-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-md-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2019 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-twitter socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>\n",
          "_cid": "rUF5jrZTi1",
          "_anchor": "footer5-a",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "connections.html": {
      "settings": {
        "meta_descr": "Website Builder Description",
        "title": "CONNECTIONS",
        "order": 1
      },
      "components": [
        {
          "alias": false,
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "-webkit-flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important",
                "-webkit-align-items": "center",
                "-webkit-justify-content": "center"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              "display": "-webkit-inline-flex",
              "align-items": "center",
              "-webkit-align-items": "center",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              }
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "-webkit-align-items": "center",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  },
                  "a": {
                    "display": "inline-flex"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "@media (min-width: 1024px)": {
                "&:not(.navbar-short) .navbar-collapse when (@showLogo)": {
                  "max-height": "~\"calc(98.5vh - @{logoSize}rem)\""
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 1023px)": {
              ".navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0",
                "-webkit-flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto",
              "-webkit-flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#232323\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.co\">\n                         <img src=\"../_images/logo2.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\">\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Space IT</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\">\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-home mbr-iconfont mbr-iconfont-btn\"></span>\n                        Services\n                    </a>\n                </li>\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-search mbr-iconfont mbr-iconfont-btn\"></span>\n                        About Us\n                    </a>\n                </li>\n            </ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\">\n                <a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.co\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a>\n            </div>\n        </div>\n    </nav>\n</section>",
          "_cid": "rUEYRSarcN",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {},
          "_anchor": "menu1-e"
        }
      ]
    },
    "u3219q.html": {
      "settings": {
        "meta_descr": "Site Generator Description",
        "title": "U3219Q",
        "order": 3
      },
      "components": [
        {
          "alias": false,
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "-webkit-flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important",
                "-webkit-align-items": "center",
                "-webkit-justify-content": "center"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              "display": "-webkit-inline-flex",
              "align-items": "center",
              "-webkit-align-items": "center",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              }
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "-webkit-align-items": "center",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  },
                  "a": {
                    "display": "inline-flex"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "@media (min-width: 1024px)": {
                "&:not(.navbar-short) .navbar-collapse when (@showLogo)": {
                  "max-height": "~\"calc(98.5vh - @{logoSize}rem)\""
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 1023px)": {
              ".navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0",
                "-webkit-flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto",
              "-webkit-flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#232323\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.co\">\n                         <img src=\"../_images/logo2.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\">\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Space IT</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\">\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-home mbr-iconfont mbr-iconfont-btn\"></span>\n                        Services\n                    </a>\n                </li>\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-search mbr-iconfont mbr-iconfont-btn\"></span>\n                        About Us\n                    </a>\n                </li>\n            </ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\">\n                <a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.co\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a>\n            </div>\n        </div>\n    </nav>\n</section>",
          "_cid": "rUEYRSarcN",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {},
          "_anchor": "menu1-b"
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/u3219q-design-large-2000x1125.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    DELL U3219Q</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Experience 4 times more detail with this 31.5” 4K Ultra HD monitor with VESA certified DisplayHDR™ 400i featuring HDR content playback support.<br></p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">BUY</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rVwGk0T6V1",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header2-c"
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">3840x2160 Ultra DH &nbsp;Incredible color.</h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Capture every element: Experience four times more detail than Full HD with 3840x2160 Ultra HD 4K resolution.<br><br>Visually stunning: Your images shine the way they were meant to on the world’s first 31.5” 4K Ultra HD monitor with VESA certified DisplayHDR™ 400i featuring HDR content playback support.<br><br>Impressive color and details: See realistic colors—from the brightest whites to the deepest darks—with a peak brightness of 400 nits, an impressive color depth of 1.07 billion colors and a high contrast ratio.<br><br>Color consistency comes standard: Your UltraSharp monitor is factory calibrated at 99% sRGB coverage to an accuracy of Delta-E less than or equal to 2, for precise hues right out of the box. And, with 95% DCI-P3 and 99% Rec. 709 color coverage, you can trust that your videos reflect lifelike color.</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rVwISU45Z9",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header16-d"
        }
      ]
    },
    "page3.html": {
      "settings": {
        "meta_descr": "Web Builder Description",
        "title": "USBC",
        "order": 2
      },
      "components": [
        {
          "alias": false,
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "-webkit-flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important",
                "-webkit-align-items": "center",
                "-webkit-justify-content": "center"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              "display": "-webkit-inline-flex",
              "align-items": "center",
              "-webkit-align-items": "center",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              }
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "-webkit-align-items": "center",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  },
                  "a": {
                    "display": "inline-flex"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "@media (min-width: 1024px)": {
                "&:not(.navbar-short) .navbar-collapse when (@showLogo)": {
                  "max-height": "~\"calc(98.5vh - @{logoSize}rem)\""
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 1023px)": {
              ".navbar-expand": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "-webkit-flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "overflow": "hidden",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0",
                "-webkit-flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto",
              "-webkit-flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#232323\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.co\">\n                         <img src=\"../_images/logo2.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\">\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Space IT</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\">\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-home mbr-iconfont mbr-iconfont-btn\"></span>\n                        Services\n                    </a>\n                </li>\n                <li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.co\" data-app-selector=\".nav-link,.dropdown-item\">\n                        <span class=\"mbri-search mbr-iconfont mbr-iconfont-btn\"></span>\n                        About Us\n                    </a>\n                </li>\n            </ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\">\n                <a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.co\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a>\n            </div>\n        </div>\n    </nav>\n</section>",
          "_cid": "rUEYRSarcN",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {},
          "_anchor": "menu1-f"
        }
      ]
    }
  }
}
