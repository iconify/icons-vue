<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i1wrjBb)" class="d2kvgvbvc"><path class="pn6mjob3r"/><path fill="url(#izNMvyc)" class="hm570mwei"/><path fill="url(#iUWMFnb)" class="hm570mwei"/><path fill="url(#ijAimZb)" class="hm570mwei"/><path fill="url(#iJ41Zcc)" class="hm570mwei"/><path fill="url(#iy0BxBe)" class="hm570mwei"/></g><path fill="url(#iEqh95d)" class="v186jnktw"/><path fill="url(#isx9Jpc)" class="v186jnktw"/><path fill="url(#ieANuAc)" class="v186jnktw"/><path fill="url(#i4n3uXN)" class="v186jnktw"/><path fill="url(#ibnNLPG)" class="v186jnktw"/><path fill="url(#iJgglId)" class="v186jnktw"/><path fill="url(#iZOGEnt)" class="jdpten60z"/><path fill="url(#ijvEP9d)" class="jdpten60z"/><path fill="url(#iCRqcKc)" class="jdpten60z"/><path fill="url(#iOmnW8b)" class="jdpten60z"/><path fill="url(#iGwet8d)" class="p7j-7kz8x"/><path fill="url(#i3eQlQb)" class="p7j-7kz8x"/><path fill="url(#iN2DTWd)" class="p7j-7kz8x"/><path fill="url(#i1jzzke)" class="p7j-7kz8x"/><g filter="url(#i2Yk1Qc)"><path stroke="url(#ims6zEb)" class="vl3wvu2wx"/></g><g filter="url(#iqSBzkd)"><path stroke="url(#iZfLMkd)" class="glgb5t3qg"/></g><g filter="url(#iGcSlBc)"><path stroke="url(#igxjWIR)" class="sxzlot88n"/></g><g filter="url(#iQdr0tb)"><path stroke="url(#iBzndRb)" class="uot1ycc4h"/></g><g filter="url(#iPakJ0c)"><path stroke="url(#icbsebb)" class="dcxs0zfdp"/></g><g filter="url(#i1NZ1Ee)"><path fill="url(#i11rrpd)" class="cyrit3yjy"/></g><path fill="url(#ilNgGIc)" clip-rule="evenodd" class="aaavajxth"/><g filter="url(#i8oPzuc)"><path stroke="url(#i3RU05v)" class="pygk6qb8z"/></g><path fill="url(#iLsMP6y)" clip-rule="evenodd" class="qy_jsf45v"/><path fill="url(#iFN4Fzc)" clip-rule="evenodd" class="qy_jsf45v"/><defs><radialGradient id="izNMvyc" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -4.125 3.93242 5.12408 16.297 19.594)" gradientUnits="userSpaceOnUse"><stop class="d1i_1uvyf"/><stop offset="1" class="v3_w39bpu"/></radialGradient><radialGradient id="iUWMFnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 18.56245 -25.6022 -.2586 16.078 13.625)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="v3_w39bpu"/><stop offset="1" class="d1i_1uvyf"/></radialGradient><radialGradient id="ijAimZb" cx="0" cy="0" r="1" gradientTransform="rotate(-40.721 35.014 -11.454)scale(5.39821 4.43849)" gradientUnits="userSpaceOnUse"><stop class="ax591ieet"/><stop offset="1" class="nt-ae80dc"/></radialGradient><radialGradient id="iJ41Zcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.00749 -1.91893 0 9.558 20.122)" gradientUnits="userSpaceOnUse"><stop class="o-1-_zgek"/><stop offset="1" class="wq49-tp5f"/></radialGradient><radialGradient id="iy0BxBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00781 .49219 -1.27635 -.02026 9.665 20.212)" gradientUnits="userSpaceOnUse"><stop class="suoxygiin"/><stop offset="1" class="jd_frioih"/></radialGradient><radialGradient id="isx9Jpc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.517 11.212 2.112)scale(9.9117 7.62008)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="leb0v626h"/><stop offset="1" class="r59vdsb4d"/></radialGradient><radialGradient id="ieANuAc" cx="0" cy="0" r="1" gradientTransform="rotate(-174.743 10.046 2.146)scale(8.33535 9.22751)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="rcixy9bea"/><stop offset="1" class="vvdtmf_do"/></radialGradient><radialGradient id="ibnNLPG" cx="0" cy="0" r="1" gradientTransform="matrix(1.47033 -3.21875 5.82387 2.66035 16.858 11.031)" gradientUnits="userSpaceOnUse"><stop class="k_2reg46q"/><stop offset=".572" class="v24o3rc5v"/></radialGradient><radialGradient id="iCRqcKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -.78125 1.4275 2.284 21.484 11.063)" gradientUnits="userSpaceOnUse"><stop class="epqdpub1b"/><stop offset="1" class="d8fnucb3s"/></radialGradient><radialGradient id="iOmnW8b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22088 -4.23548 3.63496 -4.48064 23.883 8.56)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="vkz33ubri"/><stop offset="1" class="jld9bobgs"/></radialGradient><radialGradient id="i3eQlQb" cx="0" cy="0" r="1" gradientTransform="matrix(.04249 -1.69485 4.92857 .12355 12.19 12.268)" gradientUnits="userSpaceOnUse"><stop class="hspstybgb"/><stop offset="1" class="zvfip7f_e"/></radialGradient><radialGradient id="iN2DTWd" cx="0" cy="0" r="1" gradientTransform="matrix(-12.72015 -2.73997 2.13394 -9.90668 17.478 10.888)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="s8brdj7vy"/><stop offset="1" class="m4nbaobvt"/></radialGradient><radialGradient id="i1jzzke" cx="0" cy="0" r="1" gradientTransform="rotate(119.455 5.768 9.652)scale(1.52522 3.27464)" gradientUnits="userSpaceOnUse"><stop class="y30a6bh7w"/><stop offset="1" class="iz0iibw4d"/></radialGradient><radialGradient id="ilNgGIc" cx="0" cy="0" r="1" gradientTransform="matrix(17.94785 -2.6167 3.73476 25.61648 7.915 18.267)" gradientUnits="userSpaceOnUse"><stop offset=".938" class="r3bd3p3-n"/><stop offset="1" class="ox3z_5z9v"/></radialGradient><radialGradient id="i3RU05v" cx="0" cy="0" r="1" gradientTransform="matrix(-4.01673 2.30124 -3.6321 -6.3397 23.753 14.691)" gradientUnits="userSpaceOnUse"><stop class="xu-12ddzr"/><stop offset="1" class="hao9n2ben"/></radialGradient><radialGradient id="iLsMP6y" cx="0" cy="0" r="1" gradientTransform="matrix(-15.86104 -15.23359 11.38427 -11.85317 24.6 28.151)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="c9poogb3l"/><stop offset="1" class="zkgcm7bpr"/></radialGradient><radialGradient id="iFN4Fzc" cx="0" cy="0" r="1" gradientTransform="matrix(4.45936 3.05708 -3.07415 4.48425 16 20.452)" gradientUnits="userSpaceOnUse"><stop class="r8qaojbqu"/><stop offset="1" class="yxvcvacmg"/></radialGradient><linearGradient id="iEqh95d" x1="14.437" x2="15.759" y1="8.438" y2="7.11" gradientUnits="userSpaceOnUse"><stop class="wd_5on7ia"/><stop offset="1" class="dcz0zybqr"/></linearGradient><linearGradient id="i4n3uXN" x1="21.04" x2="18.603" y1="6.985" y2="9.485" gradientUnits="userSpaceOnUse"><stop class="gkk5o_brl"/><stop offset="1" class="y8sjg0zpi"/></linearGradient><linearGradient id="iJgglId" x1="21.478" x2="20.165" y1="10.985" y2="9.235" gradientUnits="userSpaceOnUse"><stop class="l6nx4e9bi"/><stop offset="1" class="fvyef52hl"/></linearGradient><linearGradient id="iZOGEnt" x1="19.509" x2="22.237" y1="9.704" y2="9.473" gradientUnits="userSpaceOnUse"><stop class="d6qadabbx"/><stop offset="1" class="ag352nbdi"/></linearGradient><linearGradient id="ijvEP9d" x1="24.79" x2="24.032" y1="12.329" y2="11.389" gradientUnits="userSpaceOnUse"><stop class="l6nx4e9bi"/><stop offset="1" class="fvyef52hl"/></linearGradient><linearGradient id="iGwet8d" x1="7.766" x2="8.428" y1="12.813" y2="9.784" gradientUnits="userSpaceOnUse"><stop class="c712rrmet"/><stop offset="1" class="fdsobuxfm"/></linearGradient><linearGradient id="ims6zEb" x1="21.887" x2="26.775" y1="5.273" y2="7.796" gradientUnits="userSpaceOnUse"><stop class="p9y9cslha"/><stop offset="1" class="fpwlizx-k"/></linearGradient><linearGradient id="iZfLMkd" x1="16.197" x2="21.19" y1="4.922" y2="11.363" gradientUnits="userSpaceOnUse"><stop class="p9y9cslha"/><stop offset="1" class="fpwlizx-k"/></linearGradient><linearGradient id="igxjWIR" x1="9.441" x2="9.892" y1="8.615" y2="11.489" gradientUnits="userSpaceOnUse"><stop class="lbltu0bgu"/><stop offset="1" class="jb3bsacou"/></linearGradient><linearGradient id="iBzndRb" x1="9.727" x2="17.195" y1="17.274" y2="11.748" gradientUnits="userSpaceOnUse"><stop class="bq68gbj_e"/><stop offset="1" class="pyvtwrbvt"/></linearGradient><linearGradient id="icbsebb" x1="10.584" x2="17.995" y1="22.654" y2="23.12" gradientUnits="userSpaceOnUse"><stop class="ovpewx7vk"/><stop offset="1" class="u1nr9rbhh"/></linearGradient><linearGradient id="i11rrpd" x1="26.139" x2="21.165" y1="20.364" y2="11.641" gradientUnits="userSpaceOnUse"><stop class="tvy43qedp"/><stop offset="1" class="xfod64bai"/></linearGradient><filter id="i1wrjBb" width="21.365" height="26.791" x="4.758" y="2.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.439216 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1789"/></filter><filter id="i2Yk1Qc" width="6.375" height="10.781" x="19.321" y="2.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".625"/></filter><filter id="iqSBzkd" width="9.391" height="9.797" x="12.837" y="2.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".625"/></filter><filter id="iGcSlBc" width="11.703" height="5.477" x="5.473" y="6.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".625"/></filter><filter id="iQdr0tb" width="11.469" height="8.74" x="7.726" y="11.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".625"/></filter><filter id="iPakJ0c" width="10.391" height="7.415" x="8.265" y="20.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".625"/></filter><filter id="i1NZ1Ee" width="10.483" height="12.356" x="15.509" y="9.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".5"/></filter><filter id="i8oPzuc" width="8.873" height="11.495" x="16.91" y="10.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1789" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ok-hand-medium-light" /></template>
<style>
.aaavajxth {
  fill-rule: evenodd;
  d: path("M12.498 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.177-1.39c1.489 2.53 2.62 6.233 2.907 9.933l.01-.001l.015.278c.035.597.104 1.816.068 4.111c-.037 2.313-.675 4.143-1.607 5.678c-1.613 2.756-4.67 4.575-8.088 4.575c-3.787 0-6.907-2.332-8.36-5.315a2.5 2.5 0 0 1 1.733-3.542a2.504 2.504 0 0 1-2.059-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.947-.754-3.948-.805a2.5 2.5 0 1 1 .254-4.993c1.542.078 3.913.49 6.336 1.438q-.431-.467-.85-.863c-.98-.764-1.137-2.31-.373-3.29m3.32 12.419c-1.893 0-3.442.973-4.031 2.475A2.5 2.5 0 0 1 9.972 20.2c.826.089 1.59.588 1.981 1.39c.715 1.467 2.206 2.272 3.865 2.272c1.9-.15 3.541-1.663 3.541-3.802c0-2.138-1.499-3.87-3.541-3.87");
}

.ag352nbdi {
  stop-color: var(--svg-color--d69366, #D69366);
  stop-opacity: 0;
}

.ax591ieet {
  stop-color: var(--svg-color--cd9272, #CD9272);
}

.bq68gbj_e {
  stop-color: var(--svg-color--e6ae97, #E6AE97);
}

.c712rrmet {
  stop-color: var(--svg-color--b8747f, #B8747F);
}

.c9poogb3l {
  stop-color: var(--svg-color--c48e6d, #C48E6D);
  stop-opacity: 0;
}

.cyrit3yjy {
  d: path("M24.858 20.77c-1.318-8.847-6.974-9.15-8.349-9.504c2.875-1.844 7.156-.352 7.625 1.25c.906 3.094.994 6.713.724 8.255");
}

.d1i_1uvyf {
  stop-color: var(--svg-color--b77091, #B77091);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d6qadabbx {
  stop-color: var(--svg-color--d69366, #D69366);
}

.d8fnucb3s {
  stop-color: var(--svg-color--fdc79c, #FDC79C);
  stop-opacity: 0;
}

.dcxs0zfdp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M10.14 21.94c.542 1.378 2.63 4.031 6.642 3.623");
}

.dcz0zybqr {
  stop-color: var(--svg-color--d49267, #D49267);
  stop-opacity: 0;
}

.epqdpub1b {
  stop-color: var(--svg-color--fdc79c, #FDC79C);
}

.fdsobuxfm {
  stop-color: var(--svg-color--b8747f, #B8747F);
  stop-opacity: 0;
}

.fpwlizx-k {
  stop-color: var(--svg-color--ffd3aa, #FFD3AA);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvyef52hl {
  stop-color: var(--svg-color--efba97, #EFBA97);
  stop-opacity: 0;
}

.gkk5o_brl {
  stop-color: var(--svg-color--ebccb2, #EBCCB2);
}

.glgb5t3qg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M14.712 4.563c1.063.672 3.61 2.984 5.64 6.047");
}

.hao9n2ben {
  stop-color: var(--svg-color--ffd8b8, #FFD8B8);
  stop-opacity: 0;
}

.hm570mwei {
  d: path("M12.498 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.177-1.39c1.489 2.53 2.62 6.233 2.907 9.933l.01-.001l.015.278c.035.597.104 1.816.068 4.111c-.037 2.313-.675 4.143-1.607 5.678c-1.613 2.756-4.67 4.575-8.088 4.575c-3.787 0-6.907-2.332-8.36-5.315a2.5 2.5 0 0 1 1.733-3.542a2.504 2.504 0 0 1-2.059-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.947-.754-3.948-.805a2.5 2.5 0 1 1 .254-4.993c1.542.078 3.913.49 6.336 1.438q-.431-.467-.85-.863c-.98-.764-1.137-2.31-.373-3.29m3.32 12.419c-1.893 0-3.442.973-4.031 2.475A2.5 2.5 0 0 1 9.972 20.2c.826.089 1.59.588 1.981 1.39c.715 1.467 2.206 2.272 3.865 2.272c1.9-.15 3.541-1.663 3.541-3.802c0-2.138-1.499-3.87-3.541-3.87");
}

.hspstybgb {
  stop-color: var(--svg-color--cc946d, #CC946D);
}

.iz0iibw4d {
  stop-color: var(--svg-color--f1bf94, #F1BF94);
  stop-opacity: 0;
}

.jb3bsacou {
  stop-color: var(--svg-color--eebf9f, #EEBF9F);
  stop-opacity: 0;
}

.jd_frioih {
  stop-color: var(--svg-color--be7a54, #BE7A54);
  stop-opacity: 0;
}

.jdpten60z {
  d: path("M25.307 13.329c-.407-3.314-1.456-6.535-2.794-8.807a2.25 2.25 0 0 0-4.176 1.39c1.888 2.112 3.543 4.722 4.57 7.417z");
}

.jld9bobgs {
  stop-color: var(--svg-color--ca9d7c, #CA9D7C);
}

.k_2reg46q {
  stop-color: var(--svg-color--e9b288, #E9B288);
}

.l6nx4e9bi {
  stop-color: var(--svg-color--efba97, #EFBA97);
}

.lbltu0bgu {
  stop-color: var(--svg-color--eebf9f, #EEBF9F);
}

.leb0v626h {
  stop-color: var(--svg-color--c79877, #C79877);
  stop-opacity: 0;
}

.m4nbaobvt {
  stop-color: var(--svg-color--ca9b78, #CA9B78);
}

.nt-ae80dc {
  stop-color: var(--svg-color--cd9272, #CD9272);
  stop-opacity: 0;
}

.o-1-_zgek {
  stop-color: var(--svg-color--c38463, #C38463);
}

.ovpewx7vk {
  stop-color: var(--svg-color--ffcfb4, #FFCFB4);
}

.ox3z_5z9v {
  stop-color: var(--svg-color--f3c6a2, #F3C6A2);
}

.p7j-7kz8x {
  d: path("M7.385 6.487a2.5 2.5 0 0 0-.254 4.993c.99.05 2.414.299 3.897.788a9.5 9.5 0 0 1 4.926-1.363c1.217 0 2.38.227 3.452.641a2.5 2.5 0 0 0-.288-.322C15.503 7.822 10.13 6.626 7.384 6.487");
}

.p9y9cslha {
  stop-color: var(--svg-color--ffd3aa, #FFD3AA);
}

.pn6mjob3r {
  fill: var(--svg-color--efba97, #EFBA97);
  d: path("M12.498 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.177-1.39c1.489 2.53 2.62 6.233 2.907 9.933l.01-.001l.015.278c.035.597.104 1.816.068 4.111c-.037 2.313-.675 4.143-1.607 5.678c-1.613 2.756-4.67 4.575-8.088 4.575c-3.787 0-6.907-2.332-8.36-5.315a2.5 2.5 0 0 1 1.733-3.542a2.504 2.504 0 0 1-2.059-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.947-.754-3.948-.805a2.5 2.5 0 1 1 .254-4.993c1.542.078 3.913.49 6.336 1.438q-.431-.467-.85-.863c-.98-.764-1.137-2.31-.373-3.29m3.32 12.419c-1.893 0-3.442.973-4.031 2.475A2.5 2.5 0 0 1 9.972 20.2c.826.089 1.59.588 1.981 1.39c.715 1.467 2.206 2.272 3.865 2.272c1.9-.15 3.541-1.663 3.541-3.802c0-2.138-1.499-3.87-3.541-3.87");
}

.pygk6qb8z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.16 13.248c1.488.511 4.445 2.626 4.371 6.994");
}

.pyvtwrbvt {
  stop-color: var(--svg-color--e6ae97, #E6AE97);
  stop-opacity: 0;
}

.qy_jsf45v {
  fill-rule: evenodd;
  d: path("M22.783 26.051a9.4 9.4 0 0 1-6.957 3.052c-3.787 0-6.907-2.34-8.36-5.332a2.51 2.51 0 0 1 1.733-3.553a2.51 2.51 0 0 1-2.06-3.41a9.14 9.14 0 0 1 3.947-4.567l-.024-.008c1.438-.82 3.08-1.296 4.776-1.296c5.078 0 9.195 4.088 9.195 9.13c0 2.29-.848 4.382-2.25 5.984m-10.989-7.41c.59-1.507 2.14-2.483 4.032-2.483c2.042 0 3.541 1.736 3.541 3.881c0 2.146-1.64 3.663-3.541 3.813c-1.66 0-3.15-.806-3.865-2.277a2.5 2.5 0 0 0-1.981-1.396a2.5 2.5 0 0 0 1.814-1.538");
}

.r3bd3p3-n {
  stop-color: var(--svg-color--f3c6a2, #F3C6A2);
  stop-opacity: 0;
}

.r59vdsb4d {
  stop-color: var(--svg-color--c79877, #C79877);
}

.r8qaojbqu {
  stop-color: var(--svg-color--ce9371, #CE9371);
}

.rcixy9bea {
  stop-color: var(--svg-color--dda17f, #DDA17F);
  stop-opacity: 0;
}

.s8brdj7vy {
  stop-color: var(--svg-color--ca9b78, #CA9B78);
  stop-opacity: 0;
}

.suoxygiin {
  stop-color: var(--svg-color--be7a54, #BE7A54);
}

.sxzlot88n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M7.348 8.512c2.093.25 6.187 1.22 7.953 1.727");
}

.tvy43qedp {
  stop-color: var(--svg-color--f6caa4, #F6CAA4);
}

.u1nr9rbhh {
  stop-color: var(--svg-color--ffcfb4, #FFCFB4);
  stop-opacity: 0;
}

.uot1ycc4h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.727 18.068c1.187-3.406 5.093-5.062 7.468-4.687");
}

.v186jnktw {
  d: path("M12.498 3.771a2.25 2.25 0 0 1 3.158-.39c2.27 1.77 4.472 4.407 6.044 7.323h-3.17c-1.46-1.223-3.147-2.128-4.81-2.779q-.431-.467-.85-.863c-.98-.764-1.137-2.31-.373-3.29");
}

.v24o3rc5v {
  stop-color: var(--svg-color--e9b288, #E9B288);
  stop-opacity: 0;
}

.v3_w39bpu {
  stop-color: var(--svg-color--b77091, #B77091);
  stop-opacity: 0;
}

.vkz33ubri {
  stop-color: var(--svg-color--ca9d7c, #CA9D7C);
  stop-opacity: 0;
}

.vl3wvu2wx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M21.197 4.855c.625.823 2.156 4.38 2.625 7.031");
}

.vvdtmf_do {
  stop-color: var(--svg-color--dda17f, #DDA17F);
}

.wd_5on7ia {
  stop-color: var(--svg-color--d49267, #D49267);
}

.wq49-tp5f {
  stop-color: var(--svg-color--c38463, #C38463);
  stop-opacity: 0;
}

.xfod64bai {
  stop-color: var(--svg-color--f6caa4, #F6CAA4);
  stop-opacity: 0;
}

.xu-12ddzr {
  stop-color: var(--svg-color--ffd8b8, #FFD8B8);
}

.y30a6bh7w {
  stop-color: var(--svg-color--f1bf94, #F1BF94);
}

.y8sjg0zpi {
  stop-color: var(--svg-color--ebccb2, #EBCCB2);
  stop-opacity: 0;
}

.yxvcvacmg {
  stop-color: var(--svg-color--ce9371, #CE9371);
  stop-opacity: 0;
}

.zkgcm7bpr {
  stop-color: var(--svg-color--c48e6d, #C48E6D);
}

.zvfip7f_e {
  stop-color: var(--svg-color--cc946d, #CC946D);
  stop-opacity: 0;
}

</style>
