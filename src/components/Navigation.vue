<template>
    <!-- Header Section Starts Here -->
    <header>
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <nav class="menu">
                        <div class="menu__logo">
                            <a href="#">Logo</a>
                        </div>
                        <div class="menu__bar">
                            <span></span>
                            <span></span>
                            <span></span>
                        </div>
                        <ul class="menu-data">
                            <li><router-link :to="{name: 'home'}" class="active-menu">Home</router-link></li>
                            <li><router-link :to="{name: 'about'}">About</router-link></li>
                            <li><router-link :to="{name: 'services'}">Services</router-link></li>
                            <li><router-link :to="{name: 'work'}">Work</router-link></li>
                            <li><router-link :to="{name: 'blog'}">Blog</router-link></li>
                        </ul>
                        <div class="menu-button">
                            <router-link :to="{name: 'contact'}" class="btn">Hire Me</router-link>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </header>
    <!-- Header Section Ends Here-->
</template>