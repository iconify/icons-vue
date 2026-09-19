<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qgw6xmbhs"/><path fill="url(#ia0zIDN)" class="mr8bv3b1y"/><path fill="url(#iEdPaye)" class="mr8bv3b1y"/><path fill="url(#iSzSGec)" class="mr8bv3b1y"/><path fill="url(#iUS52dS)" class="mr8bv3b1y"/><path fill="url(#ikr9wGd)" class="mr8bv3b1y"/><path fill="url(#i3kePgd)" class="dcplch0ym"/><path fill="url(#iIDlDge)" class="dcplch0ym"/><path fill="url(#iPTOVIe)" class="dcplch0ym"/><g filter="url(#ilmYTDc)"><path class="pryrs7bwm"/></g><path fill="url(#iX6dmke)" class="to04fdcmw"/><path fill="url(#i07NDfe)" class="to04fdcmw"/><path fill="url(#i8DaSUt)" class="to04fdcmw"/><path fill="url(#iU1NUkc)" class="to04fdcmw"/><g filter="url(#iFKvnme)"><path class="u_qtyo8mc"/></g><path fill="url(#ibT0kCc)" class="fw0vcct2b"/><path fill="url(#iLZE6TO)" class="fw0vcct2b"/><path fill="url(#ik585rb)" class="fw0vcct2b"/><path fill="url(#iVNpjGe)" class="fw0vcct2b"/><g filter="url(#ikRl4jb)"><path class="tjo8vw_rm"/></g><g filter="url(#ikRl4jb)"><path class="qy5eh6bdk"/></g><path fill="url(#iE4fCsd)" class="pmu22pbym"/><path fill="url(#i1WYsDd)" class="pmu22pbym"/><path fill="url(#iSEumYb)" class="pmu22pbym"/><g filter="url(#i7AneHc)"><path class="us1m7tb5p"/></g><path fill="url(#i7FmnUc)" class="mg3gxgenm"/><path fill="url(#i4AVoye)" class="mg3gxgenm"/><path fill="url(#iXH535c)" class="mr8bv3b1y"/><path fill="url(#iCf13ld)" class="mr8bv3b1y"/><path fill="url(#ihSa9pX)" class="mr8bv3b1y"/><path fill="url(#iQnBE4d)" class="mr8bv3b1y"/><path fill="url(#iN95rgu)" class="v-b4eybnn"/><g filter="url(#iZF9tie)"><path stroke="url(#iIoHKsc)" class="mj7aa4bqe"/></g><g filter="url(#ibbCVkb)"><path stroke="url(#i4GpAfd)" class="wojan5yvk"/></g><g filter="url(#iydZWob)"><path stroke="url(#iTiSIKc)" class="nuzmhvb5g"/></g><g filter="url(#iYA1ugb)"><path stroke="url(#i3n7lMl)" class="f3cg-vbjw"/></g><g filter="url(#ilbcYFJ)"><path stroke="url(#iXMht5b)" class="idup4jbzx"/></g><g filter="url(#ibe0WBb)"><path fill="url(#iad1fcc)" class="bv1_q2fjy"/></g><defs><radialGradient id="ia0zIDN" cx="0" cy="0" r="1" gradientTransform="matrix(-19.41172 6.20328 -9.45813 -29.597 26.105 17.433)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="favk55-xj"/><stop offset="1" class="ouyg6rb5q"/></radialGradient><radialGradient id="iEdPaye" cx="0" cy="0" r="1" gradientTransform="matrix(-5.81574 24.215 -16.71615 -4.01473 18.294 7.814)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="ooq1zkb_k"/><stop offset="1" class="vcxu7ynaz"/></radialGradient><radialGradient id="iSzSGec" cx="0" cy="0" r="1" gradientTransform="rotate(-117.318 19.437 8.426)scale(8.58217 10.8072)" gradientUnits="userSpaceOnUse"><stop class="zky0iub6d"/><stop offset="1" class="euvf6ccek"/></radialGradient><radialGradient id="iUS52dS" cx="0" cy="0" r="1" gradientTransform="rotate(97.307 5.03 11.355)scale(22.7173 15.6822)" gradientUnits="userSpaceOnUse"><stop offset=".908" class="d1jndtiqw"/><stop offset="1" class="rute-r0sy"/></radialGradient><radialGradient id="ikr9wGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -1 4.27933 -6.01781 27.145 18.03)" gradientUnits="userSpaceOnUse"><stop class="wcg4_wbbs"/><stop offset="1" class="mydmjvw5t"/></radialGradient><radialGradient id="iPTOVIe" cx="0" cy="0" r="1" gradientTransform="rotate(87.826 .116 7.476)scale(2.17344 5.42725)" gradientUnits="userSpaceOnUse"><stop class="q5xwkebvg"/><stop offset="1" class="pxdun54aj"/></radialGradient><radialGradient id="iU1NUkc" cx="0" cy="0" r="1" gradientTransform="rotate(77.964 3.188 8.66)scale(3.35183 5.94373)" gradientUnits="userSpaceOnUse"><stop class="g1d7f8b8i"/><stop offset="1" class="ycy6bubwf"/></radialGradient><radialGradient id="iVNpjGe" cx="0" cy="0" r="1" gradientTransform="rotate(-116.651 12.728 -.292)scale(9.71133 11.3986)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="pqri2cewb"/><stop offset="1" class="c08gy1bko"/></radialGradient><radialGradient id="iSEumYb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.42492 -10.21113 11.02468 -3.6978 23.218 14.301)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="tyuv1yqgz"/><stop offset="1" class="mryqqfblh"/></radialGradient><radialGradient id="i7FmnUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.03124 -3.21097 4.18402 23.308 13.828)" gradientUnits="userSpaceOnUse"><stop class="yu-_1y2hf"/><stop offset="1" class="mn6jyi2or"/></radialGradient><radialGradient id="iXH535c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 2.12499 -1.49556 -1.25364 27.48 13.875)" gradientUnits="userSpaceOnUse"><stop class="z-sysrber"/><stop offset="1" class="abfel6bao"/></radialGradient><radialGradient id="iCf13ld" cx="0" cy="0" r="1" gradientTransform="rotate(130.365 10.165 7.614)scale(2.77561 2.99718)" gradientUnits="userSpaceOnUse"><stop class="z-sysrber"/><stop offset="1" class="abfel6bao"/></radialGradient><radialGradient id="ihSa9pX" cx="0" cy="0" r="1" gradientTransform="rotate(112.533 8.281 7.204)scale(2.69033 2.84931)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="z-sysrber"/><stop offset="1" class="abfel6bao"/></radialGradient><radialGradient id="iQnBE4d" cx="0" cy="0" r="1" gradientTransform="rotate(122.8 4.484 6.244)scale(1.41523 1.65613)" gradientUnits="userSpaceOnUse"><stop class="z-sysrber"/><stop offset="1" class="abfel6bao"/></radialGradient><radialGradient id="iN95rgu" cx="0" cy="0" r="1" gradientTransform="rotate(120.411 1.464 6.763)scale(1.41004 1.52259)" gradientUnits="userSpaceOnUse"><stop class="z-sysrber"/><stop offset="1" class="abfel6bao"/></radialGradient><radialGradient id="iad1fcc" cx="0" cy="0" r="1" gradientTransform="rotate(144.625 8.816 11.16)scale(3.83256 5.45389)" gradientUnits="userSpaceOnUse"><stop class="x1j-qdbqs"/><stop offset="1" class="x0c232b5u"/></radialGradient><linearGradient id="i3kePgd" x1="9.937" x2="8.738" y1="11.095" y2="11.123" gradientUnits="userSpaceOnUse"><stop class="w9h93uj2k"/><stop offset="1" class="ukkwbdcze"/></linearGradient><linearGradient id="iIDlDge" x1="9.633" x2="9.026" y1="13.74" y2="12.87" gradientUnits="userSpaceOnUse"><stop class="dika81glx"/><stop offset="1" class="c4_zmdbhs"/></linearGradient><linearGradient id="iX6dmke" x1="14.301" x2="12.988" y1="9.311" y2="9.405" gradientUnits="userSpaceOnUse"><stop class="w5iqacqaj"/><stop offset="1" class="xhm9uvf1n"/></linearGradient><linearGradient id="i07NDfe" x1="9.296" x2="11.693" y1="10.289" y2="10.169" gradientUnits="userSpaceOnUse"><stop class="bdtq4bcbm"/><stop offset="1" class="g9q_uuo_v"/></linearGradient><linearGradient id="i8DaSUt" x1="11.828" x2="10.934" y1="14.888" y2="11.581" gradientUnits="userSpaceOnUse"><stop offset=".405" class="dika81glx"/><stop offset="1" class="c4_zmdbhs"/></linearGradient><linearGradient id="ibT0kCc" x1="13.885" x2="15.98" y1="8.211" y2="8.107" gradientUnits="userSpaceOnUse"><stop class="w9ii644qx"/><stop offset="1" class="v5noplb4z"/></linearGradient><linearGradient id="iLZE6TO" x1="18.21" x2="17.368" y1="8.482" y2="8.473" gradientUnits="userSpaceOnUse"><stop class="t_5qhx37u"/><stop offset="1" class="sz0ahdzpe"/></linearGradient><linearGradient id="ik585rb" x1="15.98" x2="15.98" y1="13.632" y2="11.825" gradientUnits="userSpaceOnUse"><stop offset=".348" class="dika81glx"/><stop offset="1" class="c4_zmdbhs"/></linearGradient><linearGradient id="iE4fCsd" x1="17.836" x2="20.481" y1="10.408" y2="10.502" gradientUnits="userSpaceOnUse"><stop class="ql3l_ggzg"/><stop offset="1" class="tkx9folwi"/></linearGradient><linearGradient id="i1WYsDd" x1="19.233" x2="20.144" y1="14.32" y2="12.565" gradientUnits="userSpaceOnUse"><stop class="dika81glx"/><stop offset="1" class="c4_zmdbhs"/></linearGradient><linearGradient id="i4AVoye" x1="20.84" x2="22.152" y1="17.863" y2="16.547" gradientUnits="userSpaceOnUse"><stop class="ipk60rb4v"/><stop offset="1" class="oz0ieekua"/></linearGradient><linearGradient id="iIoHKsc" x1="27.245" x2="22.742" y1="15.011" y2="21.418" gradientUnits="userSpaceOnUse"><stop class="zp_thu8kx"/><stop offset="1" class="u___q54dk"/></linearGradient><linearGradient id="i4GpAfd" x1="10.072" x2="8.801" y1="14.78" y2="17.393" gradientUnits="userSpaceOnUse"><stop class="ffjgdtb0m"/><stop offset="1" class="lwqz63bje"/></linearGradient><linearGradient id="iTiSIKc" x1="14.398" x2="13.979" y1="12.933" y2="14.687" gradientUnits="userSpaceOnUse"><stop class="ffjgdtb0m"/><stop offset="1" class="lwqz63bje"/></linearGradient><linearGradient id="i3n7lMl" x1="18.227" x2="18.149" y1="13.078" y2="13.875" gradientUnits="userSpaceOnUse"><stop class="ffjgdtb0m"/><stop offset="1" class="lwqz63bje"/></linearGradient><linearGradient id="iXMht5b" x1="22.332" x2="20.893" y1="15.511" y2="16.699" gradientUnits="userSpaceOnUse"><stop class="ffjgdtb0m"/><stop offset="1" class="lwqz63bje"/></linearGradient><filter id="ilmYTDc" width="4.609" height="10.585" x="5.934" y="6.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".5"/></filter><filter id="iFKvnme" width="4.647" height="11.076" x="10.142" y="4.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".5"/></filter><filter id="ikRl4jb" width="3.365" height="12.11" x="15.373" y="2.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".5"/></filter><filter id="i7AneHc" width="3.365" height="12.11" x="20.006" y="4.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".5"/></filter><filter id="iZF9tie" width="7.344" height="8.406" x="21.175" y="12.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".5"/></filter><filter id="ibbCVkb" width="3.344" height="3.406" x="7.215" y="13.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".25"/></filter><filter id="iydZWob" width="3.656" height="2.594" x="11.183" y="11.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".25"/></filter><filter id="iYA1ugb" width="3.794" height="1.975" x="14.855" y="12.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".25"/></filter><filter id="ilbcYFJ" width="2.438" height="2.906" x="20.574" y="14.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".25"/></filter><filter id="ibe0WBb" width="5.031" height="5.219" x="17.762" y="13.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1512" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-hand-medium" /></template>
<style>
.abfel6bao {
  stop-color: var(--svg-color--c69f87, #C69F87);
  stop-opacity: 0;
}

.bdtq4bcbm {
  stop-color: var(--svg-color--825a4c, #825A4C);
}

.bv1_q2fjy {
  d: path("M22.293 15.203c-1.75-.012-3.427-1.052-3.969-1.5c-.4 2.163 1.24 3.766 2.078 4.219z");
}

.c08gy1bko {
  stop-color: var(--svg-color--a28268, #A28268);
}

.c4_zmdbhs {
  stop-color: var(--svg-color--b5887c, #B5887C);
  stop-opacity: 0;
}

.d1jndtiqw {
  stop-color: var(--svg-color--9a5987, #9A5987);
  stop-opacity: 0;
}

.dcplch0ym {
  d: path("m5.46 14.129l-.187-4.42a2.332 2.332 0 0 1 4.071-1.651v-.009c.179.237.452.744.496 1.496c.056.97.17 3.367.219 4.446z");
}

.dika81glx {
  stop-color: var(--svg-color--b5887c, #B5887C);
}

.euvf6ccek {
  stop-color: var(--svg-color--bd8a82, #BD8A82);
  stop-opacity: 0;
}

.f3cg-vbjw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.605 12.984c.61.313 1.64.579 2.294.436");
}

.favk55-xj {
  stop-color: var(--svg-color--916761, #916761);
  stop-opacity: 0;
}

.ffjgdtb0m {
  stop-color: var(--svg-color--c19985, #C19985);
}

.ft5dv1b6b {
  fill: none;
}

.fw0vcct2b {
  d: path("M18.162 6.284c0-.457.166-.864.264-.977v-.003l-.022-.965a2.416 2.416 0 1 0-4.83.114l.02.83c.294.53.31 1.133.324 1.724c.044 1.81.27 4.172.387 5.98h3.736c.026-1.966.12-6.059.12-6.703");
}

.g1d7f8b8i {
  stop-color: var(--svg-color--a18067, #A18067);
}

.g9q_uuo_v {
  stop-color: var(--svg-color--825a4c, #825A4C);
  stop-opacity: 0;
}

.idup4jbzx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.324 16.61c.266-.391.734-1.172.938-1.407");
}

.ipk60rb4v {
  stop-color: var(--svg-color--b6897d, #B6897D);
}

.lwqz63bje {
  stop-color: var(--svg-color--c19985, #C19985);
  stop-opacity: 0;
}

.mg3gxgenm {
  d: path("m22.793 14.672l1.325-1.645a2.516 2.516 0 0 1 3.919 3.159l-.623.773l-.006.009a45 45 0 0 0-3.217 4.663c-.427.641-.804 1.322-1.175 2.005c-3.158-1.687-2.697-4.863-1.995-6.357z");
}

.mj7aa4bqe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M26.769 14.644c-.744.745-2.555 2.768-3.844 4.906");
}

.mn6jyi2or {
  stop-color: var(--svg-color--855f49, #855F49);
  stop-opacity: 0;
}

.mr8bv3b1y {
  d: path("M13.57 4.453a2.416 2.416 0 1 1 4.83-.114l.023.973a2.407 2.407 0 0 1 4.5 1.26l-.255 8.255l1.45-1.8a2.516 2.516 0 1 1 3.919 3.159l-.623.773l-.006.009a45 45 0 0 0-3.217 4.663c-.474.712-.886 1.472-1.298 2.231c-.587 1.083-1.172 2.162-1.935 3.095a8.25 8.25 0 0 1-6.423 3.063a8.26 8.26 0 0 1-7.276-4.342l-.005.008C5.98 23.405 5.793 20.881 5.73 19.53l-.137-2.442a2 2 0 0 1-.015-.19l-.305-7.19a2.332 2.332 0 0 1 4.071-1.65l-.047-1.406a2.34 2.34 0 0 1 4.293-1.368z");
}

.mryqqfblh {
  stop-color: var(--svg-color--987962, #987962);
}

.mydmjvw5t {
  stop-color: var(--svg-color--a9817c, #A9817C);
  stop-opacity: 0;
}

.nuzmhvb5g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.933 13.813c.657-.25 1.682-.744 2.157-1.094");
}

.ooq1zkb_k {
  stop-color: var(--svg-color--99597d, #99597D);
  stop-opacity: 0;
}

.ouyg6rb5q {
  stop-color: var(--svg-color--916761, #916761);
}

.oz0ieekua {
  stop-color: var(--svg-color--b6897d, #B6897D);
  stop-opacity: 0;
}

.pmu22pbym {
  d: path("M18.422 5.307c-.098.113-.265.52-.265.977c0 2.606-.12 4.52-.12 7.126l4.631 3.316v-1.901l.256-8.253a2.407 2.407 0 0 0-4.501-1.26v-.007z");
}

.pqri2cewb {
  stop-color: var(--svg-color--a28268, #A28268);
  stop-opacity: 0;
}

.pryrs7bwm {
  fill: var(--svg-color--c69f88, #C69F88);
  d: path("M8.028 9.416c-.1-1.07-.641-1.296-1.094-1.296c1.219-.532 2.125.187 2.219 1.296l.39 5.188l-1.953 1.922l.766-2.188c0-1.229-.235-3.921-.328-4.922");
}

.pxdun54aj {
  stop-color: var(--svg-color--9d7e66, #9D7E66);
  stop-opacity: 0;
}

.q5xwkebvg {
  stop-color: var(--svg-color--9d7e66, #9D7E66);
}

.qgw6xmbhs {
  fill: var(--svg-color--b5887c, #B5887C);
  d: path("M13.57 4.453a2.416 2.416 0 1 1 4.83-.114l.023.973a2.407 2.407 0 0 1 4.5 1.26l-.255 8.255l1.45-1.8a2.516 2.516 0 1 1 3.919 3.159l-.623.773l-.006.009a45 45 0 0 0-3.217 4.663c-.474.712-.886 1.472-1.298 2.231c-.587 1.083-1.172 2.162-1.935 3.095a8.25 8.25 0 0 1-6.423 3.063a8.26 8.26 0 0 1-7.276-4.342l-.005.008C5.98 23.405 5.793 20.881 5.73 19.53l-.137-2.442a2 2 0 0 1-.015-.19l-.305-7.19a2.332 2.332 0 0 1 4.071-1.65l-.047-1.406a2.34 2.34 0 0 1 4.293-1.368z");
}

.ql3l_ggzg {
  stop-color: var(--svg-color--84564c, #84564C);
}

.qy5eh6bdk {
  fill: var(--svg-color--c69f88, #C69F88);
  d: path("M16.373 3.008v10.11h1.203c.054-2.124.162-6.749.162-8.257s-.91-1.864-1.365-1.853");
}

.rute-r0sy {
  stop-color: var(--svg-color--9a5987, #9A5987);
}

.sz0ahdzpe {
  stop-color: var(--svg-color--99735b, #99735B);
  stop-opacity: 0;
}

.t_5qhx37u {
  stop-color: var(--svg-color--99735b, #99735B);
}

.tjo8vw_rm {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("M16.373 3.008v10.11h1.203c.054-2.124.162-6.749.162-8.257s-.91-1.864-1.365-1.853");
}

.tkx9folwi {
  stop-color: var(--svg-color--84564c, #84564C);
  stop-opacity: 0;
}

.to04fdcmw {
  d: path("M9.344 8.05c.179.236.452.743.496 1.495c.035.6.231 3.923.342 5.643l4.178-1.172l-.443-6.88c-.017-.632-.011-1.285-.327-1.853a2.34 2.34 0 0 0-4.292 1.368z");
}

.tyuv1yqgz {
  stop-color: var(--svg-color--987962, #987962);
  stop-opacity: 0;
}

.u___q54dk {
  stop-color: var(--svg-color--c29186, #C29186);
  stop-opacity: 0;
}

.u_qtyo8mc {
  fill: var(--svg-color--c69f88, #C69F88);
  d: path("M12.236 6.529c-.1-1.07-.64-1.297-1.094-1.297c1.219-.532 2.125.187 2.219 1.297l.428 6.668l-2.014.932l.842-1.864c0-1.229-.287-4.736-.381-5.736");
}

.ukkwbdcze {
  stop-color: var(--svg-color--a97d6c, #A97D6C);
  stop-opacity: 0;
}

.us1m7tb5p {
  fill: var(--svg-color--c69f88, #C69F88);
  d: path("M21.007 5.078v10.11h1.202c.054-2.124.163-6.748.163-8.257s-.91-1.864-1.366-1.853");
}

.v-b4eybnn {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M13.57 4.453a2.416 2.416 0 1 1 4.83-.114l.023.973a2.407 2.407 0 0 1 4.5 1.26l-.255 8.255l1.45-1.8a2.516 2.516 0 1 1 3.919 3.159l-.623.773l-.006.009a45 45 0 0 0-3.217 4.663c-.474.712-.886 1.472-1.298 2.231c-.587 1.083-1.172 2.162-1.935 3.095a8.25 8.25 0 0 1-6.423 3.063a8.26 8.26 0 0 1-7.276-4.342l-.005.008C5.98 23.405 5.793 20.881 5.73 19.53l-.137-2.442a2 2 0 0 1-.015-.19l-.305-7.19a2.332 2.332 0 0 1 4.071-1.65l-.047-1.406a2.34 2.34 0 0 1 4.293-1.368z");
}

.v5noplb4z {
  stop-color: var(--svg-color--84584b, #84584B);
  stop-opacity: 0;
}

.vcxu7ynaz {
  stop-color: var(--svg-color--99597d, #99597D);
}

.w5iqacqaj {
  stop-color: var(--svg-color--a57b69, #A57B69);
}

.w9h93uj2k {
  stop-color: var(--svg-color--a97d6c, #A97D6C);
}

.w9ii644qx {
  stop-color: var(--svg-color--84584b, #84584B);
}

.wcg4_wbbs {
  stop-color: var(--svg-color--a9817c, #A9817C);
}

.wojan5yvk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.808 14.406c-.291.344-1.28 1.344-1.843 1.906");
}

.x0c232b5u {
  stop-color: var(--svg-color--c29a87, #C29A87);
  stop-opacity: 0;
}

.x1j-qdbqs {
  stop-color: var(--svg-color--c29a87, #C29A87);
}

.xhm9uvf1n {
  stop-color: var(--svg-color--a57b69, #A57B69);
  stop-opacity: 0;
}

.ycy6bubwf {
  stop-color: var(--svg-color--a18067, #A18067);
  stop-opacity: 0;
}

.yu-_1y2hf {
  stop-color: var(--svg-color--855f49, #855F49);
}

.z-sysrber {
  stop-color: var(--svg-color--c69f87, #C69F87);
}

.zky0iub6d {
  stop-color: var(--svg-color--bd8a82, #BD8A82);
}

.zp_thu8kx {
  stop-color: var(--svg-color--c29186, #C29186);
}

</style>
