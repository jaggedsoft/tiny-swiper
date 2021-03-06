---
id: demo
title: Demos
---
import {
    SwiperPluginPagination,
    SwiperPluginLazyload,
    SwiperPluginKeyboardControl,
    SwiperPluginMousewheel
} from 'tiny-swiper/lib/index.esm'
import Demo from '../../src/components/Demo'

## Basic

### Default Setup

<Demo
    option={{}}
    demoID="tiny-swiper2-basic-demo">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>


### Loop mode

<Demo
    option={{
        loop: true
    }}
    demoID="tiny-swiper2-demo-loop-mode">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>


### FreeMode

<Demo
    option={{
        freeMode: true,
        loop: true
    }}
    demoID="tiny-swiper2-demo-freemode">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>

### Vertical Slider

<Demo
    option={{
        direction: 'vertical'
    }}
    demoID="tiny-swiper2-demo-vertical-slider">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>

### Space Between Slides

<Demo
    option={{
        spaceBetween: 100
    }}
    demoID="tiny-swiper2-demo-space-between-slides">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>

### Speed Control

<Demo
    option={{
        speed: 2000
    }}
    demoID="tiny-swiper2-demo-speed-control">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>

### Resistance Control

With less resistanceRatio comes bigger resistance.

<Demo
    option={{
        resistance: false
    }}
    demoID="tiny-swiper2-demo-resistance-control">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>


## Plugins

### Pagination

You need to implement CSS code yourself.

<Demo
    option={{
        pagination: {
            el: '.swiper-plugin-pagination',
            clickable: true,
            bulletClass: 'swiper-plugin-pagination__item',
            bulletActiveClass: 'is-active'
        },
        plugins: [
            SwiperPluginPagination
        ]
    }}
    demoID="tiny-swiper2-demo-plugin-pagination">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
        <div className="swiper-plugin-pagination"></div>
    </div>
</Demo>

### Lazyload

<Demo
    option={{
        lazyload: {
            loadPrevNext: false,
            loadPrevNextAmount: 1,
            loadOnTransitionStart: false,
            elementClass: 'swiper-lazy',
            loadingClass: 'swiper-lazy-loading',
            loadedClass: 'swiper-lazy-loaded',
            preloaderClass: 'swiper-lazy-preloader'
        },
        plugins: [
            SwiperPluginLazyload
        ]
    }}
    demoID="tiny-swiper2-demo-plugin-plugin-lazyload">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img
                    className="swiper-lazy"
                    data-src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
                <div className="swiper-lazy-preloader"></div>
            </div>
            <div className="swiper-slide">
                <img
                    className="swiper-lazy"
                    data-src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
                <div className="swiper-lazy-preloader"></div>
            </div>
            <div className="swiper-slide">
                <img
                    className="swiper-lazy"
                    data-src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
                <div className="swiper-lazy-preloader"></div>
            </div>
            <div className="swiper-slide">
                <img
                    className="swiper-lazy"
                    data-src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
                <div className="swiper-lazy-preloader"></div>
            </div>
            <div className="swiper-slide">
                <img
                    className="swiper-lazy"
                    data-src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
                <div className="swiper-lazy-preloader"></div>
            </div>
        </div>
    </div>
</Demo>

### Keyboard Control

Using `up` `right` `down` `left` keys to control swiper instance.

Keys `up` and `down` work only when `direction: vertical`, so do `right` and `left`.

<Demo
    option={{
        keyboard: {
            enabled: true
        },
        plugins: [
            SwiperPluginKeyboardControl
        ]
    }}
    demoID="tiny-swiper2-demo-plugin-plugin-keyboardcontrol">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
        <div className="swiper-plugin-pagination"></div>
    </div>
</Demo>

### Mousewheel

<Demo
    option={{
        mousewheel: {
            invert: false,
            interval: 100
        },
        plugins: [
            SwiperPluginMousewheel
        ]
    }}
    demoID="tiny-swiper2-demo-plugin-plugin-mousewheel">
    <div className="swiper-container">
        <div className="swiper-wrapper">
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327273-74284900-3fc0-11eb-913a-69661b73ab5d.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327264-712d5880-3fc0-11eb-8f07-7d58264938c1.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327260-6f639500-3fc0-11eb-85fa-cfaa45ce054c.png"/>
            </div>
            <div className="swiper-slide">
                <img src="https://user-images.githubusercontent.com/10026019/102327267-72f71c00-3fc0-11eb-8550-8845f38935a4.png"/>
            </div>
        </div>
    </div>
</Demo>
