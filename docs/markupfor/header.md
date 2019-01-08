# Markup for Header component



```html
<header class="header">

    <div class="container">
        <nav>

            <a href="#"><h1 class="logo"></h1></a>

            <ul role="menubar">
                <li>
                    <a href="#"
                        role="menuitem"
                        tabindex="1">Home</a>
                </li>
                <li>
                    <a href="#"
                        role="menuitem"
                        aria-haspopup="true"
                        aria-expaned="false"
                        tabindex="2"
                    >About</a>

                    <ul role="menu"
                        aria-label="About">
                        <li role="none">
                            <a role="menuitem"
                                href="#"
                                tabindex="-1">About us</a>
                        </li>
                        <li role="none">
                            <a role="menuitem"
                                href="#"
                                tabindex="-1">About our work</a>
                        </li>
                    </ul>

                </li>

                <li>
                    <a href="#"
                       role="menuitem">Sign in</a>
                </li>
            </ul>

        </nav>
    </div>

</header>
```
