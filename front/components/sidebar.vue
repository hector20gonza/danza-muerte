<template>
    <div class="layout has-sidebar fixed-sidebar fixed-header">
      <aside id="sidebar" class="sidebar break-point-sm has-bg-image">
        <a id="btn-collapse" class="sidebar-collapser"><i class="ri-arrow-left-s-line"></i></a>
        <div class="image-wrapper">
          <img src="assets/images/sidebar-bg.jpg" alt="sidebar background" />
        </div>
        <div class="sidebar-layout">
          <div class="sidebar-header">
            <div class="pro-sidebar-logo">
              <div>P</div>
              <h5>Pro Sidebar</h5>
            </div>
          </div>
          <div class="sidebar-content">
            <nav class="menu open-current-submenu">
              <ul>
                <li class="menu-header"><span> GENERAL </span></li>
                <li class="menu-item sub-menu">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-vip-diamond-fill"></i>
                    </span>
                    <span class="menu-title">Components</span>
                    <span class="menu-suffix">
                      <span class="badge primary">Hot</span>
                    </span>
                  </a>
                  <div class="sub-menu-list">
                    <ul>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Grid</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Layout</span>
                        </a>
                      </li>
                      <li class="menu-item sub-menu">
                        <a href="#">
                          <span class="menu-title">Forms</span>
                        </a>
                        <div class="sub-menu-list">
                          <ul>
                            <li class="menu-item">
                              <a href="#">
                                <span class="menu-title">Input</span>
                              </a>
                            </li>
                            <li class="menu-item">
                              <a href="#">
                                <span class="menu-title">Select</span>
                              </a>
                            </li>
                            <li class="menu-item sub-menu">
                              <a href="#">
                                <span class="menu-title">More</span>
                              </a>
                              <div class="sub-menu-list">
                                <ul>
                                  <li class="menu-item">
                                    <a href="#">
                                      <span class="menu-title">CheckBox</span>
                                    </a>
                                  </li>
                                  <li class="menu-item">
                                    <a href="#">
                                      <span class="menu-title">Radio</span>
                                    </a>
                                  </li>
                                  <li class="menu-item sub-menu">
                                    <a href="#">
                                      <span class="menu-title">Want more ?</span>
                                      <span class="menu-suffix">&#x1F914;</span>
                                    </a>
                                    <div class="sub-menu-list">
                                      <ul>
                                        <li class="menu-item">
                                          <a href="#">
                                            <span class="menu-prefix">&#127881;</span>
                                            <span class="menu-title">You made it </span>
                                          </a>
                                        </li>
                                      </ul>
                                    </div>
                                  </li>
                                </ul>
                              </div>
                            </li>
                          </ul>
                        </div>
                      </li>
                    </ul>
                  </div>
                </li>
                <li class="menu-item sub-menu">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-bar-chart-2-fill"></i>
                    </span>
                    <span class="menu-title">Charts</span>
                  </a>
                  <div class="sub-menu-list">
                    <ul>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Pie chart</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Line chart</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Bar chart</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </li>
                <li class="menu-item sub-menu">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-shopping-cart-fill"></i>
                    </span>
                    <span class="menu-title">E-commerce</span>
                  </a>
                  <div class="sub-menu-list">
                    <ul>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Products</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Orders</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">credit card</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </li>
                <li class="menu-item sub-menu">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-global-fill"></i>
                    </span>
                    <span class="menu-title">Maps</span>
                  </a>
                  <div class="sub-menu-list">
                    <ul>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Google maps</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Open street map</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </li>
                <li class="menu-item sub-menu">
                  <a href="#">
                    <span class="menu-icon">
                     <i class="ri-paint-brush-fill"></i>
                    </span>
                    <span class="menu-title">Theme</span>
                  </a>
                  <div class="sub-menu-list">
                    <ul>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Dark</span>
                        </a>
                      </li>
                      <li class="menu-item">
                        <a href="#">
                          <span class="menu-title">Light</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </li>
                <li class="menu-header" style="padding-top: 20px"><span> EXTRA </span></li>
                <li class="menu-item">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-book-2-fill"></i>
                    </span>
                    <span class="menu-title">Documentation</span>
                    <span class="menu-suffix">
                      <span class="badge secondary">Beta</span>
                    </span>
                  </a>
                </li>
                <li class="menu-item">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-calendar-fill"></i>
                    </span>
                    <span class="menu-title">Calendar</span>
                  </a>
                </li>
                <li class="menu-item">
                  <a href="#">
                    <span class="menu-icon">
                      <i class="ri-service-fill"></i>
                    </span>
                    <span class="menu-title">Examples</span>
                  </a>
                </li>
              </ul>
            </nav>
          </div>
          <div class="sidebar-footer">
            <div class="footer-box">
              <div>
                <img
                  class="react-logo"
                  src="https://user-images.githubusercontent.com/25878302/213938106-ca8f0485-3f30-4861-9188-2920ed7ab284.png"
                  alt="react"
                />
              </div>
              <div style="padding: 0 10px">
                <span style="display: block; margin-bottom: 10px"
                  >Pro sidebar is also available as a react package
                </span>
                <div style="margin-bottom: 15px">
                  <img
                    alt="preview badge"
                    src="https://img.shields.io/github/stars/azouaoui-med/react-pro-sidebar?style=social"
                  />
                </div>
                <div>
                  <a href="https://github.com/azouaoui-med/react-pro-sidebar" target="_blank"
                    >Check it out!</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </aside>
      <div id="overlay" class="overlay"></div>
      <div class="layout">
        <main class="content">
          <div>
            <a id="btn-toggle" href="#" class="sidebar-toggler break-point-sm">
              <i class="ri-menu-line ri-xl"></i>
            </a>
            <h1 style="margin-bottom: 0">Pro Sidebar</h1>
            <span style="display: inline-block">
              Responsive layout with advanced sidebar menu built with SCSS and vanilla Javascript
            </span>
            <br />
            <span>
              Full Code and documentation available on
              <a href="https://github.com/azouaoui-med/pro-sidebar-template" target="_blank"
                >Github</a
              >
            </span>
            <div style="margin-top: 10px">
              <a href="https://github.com/azouaoui-med/pro-sidebar-template" target="_blank">
                <img
                  alt="GitHub stars"
                  src="https://img.shields.io/github/stars/azouaoui-med/pro-sidebar-template?style=social"
                />
              </a>
              <a href="https://github.com/azouaoui-med/pro-sidebar-template" target="_blank">
                <img
                  alt="GitHub forks"
                  src="https://img.shields.io/github/forks/azouaoui-med/pro-sidebar-template?style=social"
                />
              </a>
            </div>
          </div>
          <div>
            <h2>Features</h2>
            <ul>
              <li>Fully responsive</li>
              <li>Collapsable sidebar</li>
              <li>Multi level menu</li>
              <li>RTL support</li>
              <li>Customizable</li>
            </ul>
          </div>
          <div>
            <h2>Resources</h2>
            <ul>
              <li>
                <a target="_blank" href="https://github.com/azouaoui-med/css-pro-layout">
                  Css Pro Layout</a
                >
              </li>
              <li>
                <a target="_blank" href="https://github.com/popperjs/popper-core"> Popper Core</a>
              </li>
              <li>
                <a target="_blank" href="https://remixicon.com/"> Remix Icons</a>
              </li>
            </ul>
          </div>
          <footer class="footer">
            <small style="margin-bottom: 20px; display: inline-block">
              © 2023 made with
              <span style="color: red; font-size: 18px">&#10084;</span> by -
              <a target="_blank" href="https://azouaoui.netlify.com"> Mohamed Azouaoui </a>
            </small>
            <br />
            <div class="social-links">
              <a href="https://github.com/azouaoui-med" target="_blank">
                <i class="ri-github-fill ri-xl"></i>
              </a>
              <a href="https://twitter.com/azouaoui_med" target="_blank">
                <i class="ri-twitter-fill ri-xl"></i>
              </a>
              <a href="https://codepen.io/azouaoui-med" target="_blank">
                <i class="ri-codepen-fill ri-xl"></i>
              </a>
              <a href="https://www.linkedin.com/in/mohamed-azouaoui/" target="_blank">
                <i class="ri-linkedin-box-fill ri-xl"></i>
              </a>
            </div>
          </footer>
        </main>
        <div class="overlay"></div>
      </div>
    </div>
</template>