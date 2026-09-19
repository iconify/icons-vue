<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iftq4ze)" class="fu8-bsboc"/><path fill="url(#iIpwJhb)" class="fu8-bsboc"/><path fill="url(#ihkngUb)" class="fu8-bsboc"/><path fill="url(#iAhfxkd)" class="fu8-bsboc"/><path fill="url(#im46DKc)" class="fu8-bsboc"/><path fill="url(#iXdS6eb)" class="fu8-bsboc"/><path fill="url(#iXYwz6E)" class="fu8-bsboc"/><g filter="url(#iojEcyV)"><path class="wk94u01pc"/><path fill="url(#i8wBmbc)" class="b8a0bvb3f"/><path fill="url(#ilHEaqc)" class="b8a0bvb3f"/><path fill="url(#iukM6Kg)" class="b8a0bvb3f"/></g><path class="pp8dtty2m"/><path fill="url(#i3gmaOe)" class="h-5-hz00x"/><path fill="url(#iZWV9ee)" class="aj5600bwk"/><path fill="url(#iMsVRKc)" class="aj5600bwk"/><g filter="url(#ib2SmBL)"><path fill="url(#ihZjPtd)" class="nba_7yb5n"/><path fill="url(#iTB81kc)" class="nba_7yb5n"/></g><g filter="url(#ipN8nRb)"><path fill="url(#iE4Mqzb)" class="v2fe1msxm"/></g><path class="ioz-tabvp"/><path fill="url(#iEblsde)" class="hrzqfp8ld"/><path fill="url(#inaw8Mc)" class="hrzqfp8ld"/><path fill="url(#i49K0Ec)" class="hrzqfp8ld"/><g filter="url(#i4SFY2d)"><path fill="url(#i4HDmOc)" class="pgzs8yw1z"/></g><path class="vk7uuyb3q"/><path fill="url(#ima0Svc)" class="gqsj52v9c"/><path fill="url(#i2tU1wd)" class="gqsj52v9c"/><path fill="url(#i7OuNGe)" class="gqsj52v9c"/><g filter="url(#iZZs4qe)"><path class="pywz8_b9k"/></g><g filter="url(#iCoo9oc)"><path class="pscv-abgd"/></g><path fill="url(#iToMlXd)" class="hf75rvuwe"/><g filter="url(#iPzv7cC)"><path class="vabrk7b0x"/></g><path fill="url(#i1P1QEb)" class="elzm1fbwf"/><path fill="url(#iKKiSxB)" class="fe39-9boy"/><g filter="url(#iUdAqEd)"><path fill="url(#i0PEqzf)" class="i9e54sb-f"/></g><g filter="url(#iBX4qWd)"><path fill="url(#iMpC7le)" class="khi6flbrh"/></g><g filter="url(#iUCaPXc)"><path fill="url(#iMuFJSd)" class="adfwf0ayq"/></g><path fill="url(#iILrdcG)" clip-rule="evenodd" class="g3g7i3ydq"/><path fill="url(#iJR246c)" clip-rule="evenodd" class="wwqfcw0le"/><path fill="url(#iUDTiOn)" clip-rule="evenodd" class="jlxj8cckj"/><defs><radialGradient id="iIpwJhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 1.84375 -1.2524 1.08259 21.375 3.719)" gradientUnits="userSpaceOnUse"><stop class="xbiw5hcif"/><stop offset="1" class="nsr-ftbsg"/></radialGradient><radialGradient id="ihkngUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -7.1875 0 25.969 6.5)" gradientUnits="userSpaceOnUse"><stop class="vh43avbco"/><stop offset="1" class="eey99_bhz"/></radialGradient><radialGradient id="iAhfxkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.24219 -4.69078 0 15.813 3.906)" gradientUnits="userSpaceOnUse"><stop class="lvqk0nqky"/><stop offset="1" class="gahlekbea"/></radialGradient><radialGradient id="im46DKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -4.72028 0 15.813 6.281)" gradientUnits="userSpaceOnUse"><stop class="lvqk0nqky"/><stop offset="1" class="gahlekbea"/></radialGradient><radialGradient id="iXdS6eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -12.6481 0 18 8.469)" gradientUnits="userSpaceOnUse"><stop class="sijfm5c7g"/><stop offset=".695" class="em5n3nbos"/></radialGradient><radialGradient id="iXYwz6E" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.60937 -.62628 0 18.031 4.688)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="wzoz5-bzo"/><stop offset="1" class="t7ticbb7k"/></radialGradient><radialGradient id="ilHEaqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.15625 -.65625 0 16.094 7.75)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ehc3c6bri"/><stop offset="1" class="sm03mgz8i"/></radialGradient><radialGradient id="iukM6Kg" cx="0" cy="0" r="1" gradientTransform="rotate(90 3.875 10)scale(3.875 1.75)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ehc3c6bri"/><stop offset="1" class="sm03mgz8i"/></radialGradient><radialGradient id="i3gmaOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -11.1991 0 15.95 29.063)" gradientUnits="userSpaceOnUse"><stop class="mib97vbha"/><stop offset="1" class="swi2z_sri"/></radialGradient><radialGradient id="iTB81kc" cx="0" cy="0" r="1" gradientTransform="rotate(87.166 -4.726 17.39)scale(6.32023 15.3933)" gradientUnits="userSpaceOnUse"><stop class="euyaskkzn"/><stop offset="1" class="n35fembwl"/></radialGradient><radialGradient id="iEblsde" cx="0" cy="0" r="1" gradientTransform="scale(23.4537 15.1875)rotate(90 -.106 1.1)" gradientUnits="userSpaceOnUse"><stop class="r3voajbgm"/><stop offset=".424" class="hdmk_hbvo"/><stop offset=".846" class="skh2d796p"/></radialGradient><radialGradient id="inaw8Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.4375 -28.2977 0 15.95 26.688)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="eihz2rbpj"/><stop offset=".653" class="xkmxg0b0o"/></radialGradient><radialGradient id="i49K0Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-4.92592 8.43747 -6.6206 -3.8652 20.875 17.5)" gradientUnits="userSpaceOnUse"><stop class="o1e0fx-wd"/><stop offset="1" class="eztutqbym"/></radialGradient><radialGradient id="ima0Svc" cx="0" cy="0" r="1" gradientTransform="matrix(1 3.73438 -7.40445 1.98278 21.438 17.64)" gradientUnits="userSpaceOnUse"><stop class="p8f1q_bno"/><stop offset="1" class="l7n_cpb3w"/></radialGradient><radialGradient id="i2tU1wd" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 9 -14.78657 1.33488 17.313 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="qy1gwjb9k"/><stop offset=".714" class="o61sdac3w"/><stop offset="1" class="huvm4e9pq"/></radialGradient><radialGradient id="i7OuNGe" cx="0" cy="0" r="1" gradientTransform="rotate(99.34 1.338 16.73)scale(9.62764 12.5668)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="q9pw6jbml"/><stop offset=".729" class="pv1204byr"/></radialGradient><radialGradient id="iToMlXd" cx="0" cy="0" r="1" gradientTransform="rotate(136.169 3.091 11.836)scale(2.19216)" gradientUnits="userSpaceOnUse"><stop class="xoj332bzf"/><stop offset=".848" class="n3j0clbkp"/></radialGradient><radialGradient id="i1P1QEb" cx="0" cy="0" r="1" gradientTransform="rotate(136.169 5.408 10.563)scale(2.16597)" gradientUnits="userSpaceOnUse"><stop class="he2380b3g"/><stop offset=".847" class="n3j0clbkp"/></radialGradient><radialGradient id="iKKiSxB" cx="0" cy="0" r="1" gradientTransform="rotate(136.169 6.289 13.216)scale(2.19946)" gradientUnits="userSpaceOnUse"><stop class="lb0wcwbqp"/><stop offset=".82" class="fq32t0a9q"/></radialGradient><radialGradient id="iMpC7le" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 3.99999 -5.2941 -7.32078 24.976 20.078)" gradientUnits="userSpaceOnUse"><stop class="uqwr-l9qe"/><stop offset="1" class="j97kxmblv"/></radialGradient><linearGradient id="iftq4ze" x1="13.2" x2="29.375" y1="5.148" y2="5.148" gradientUnits="userSpaceOnUse"><stop class="b5kunqbww"/><stop offset=".055" class="ng50wy7rm"/><stop offset=".884" class="usqk13ums"/><stop offset="1" class="wxmbkqb0o"/></linearGradient><linearGradient id="i8wBmbc" x1="17.344" x2="18.75" y1="5.656" y2="5.656" gradientUnits="userSpaceOnUse"><stop class="iss3dtg2x"/><stop offset=".467" class="t327bcbwo"/><stop offset="1" class="smna-rb4b"/></linearGradient><linearGradient id="iZWV9ee" x1="2" x2="29.125" y1="19.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="g8ku9uqgn"/><stop offset="1" class="lsrjxdbyj"/></linearGradient><linearGradient id="iMsVRKc" x1="16.015" x2="16.015" y1="12.328" y2="28.219" gradientUnits="userSpaceOnUse"><stop offset=".542" class="nioqxz-4b"/><stop offset="1" class="woe16jbzr"/></linearGradient><linearGradient id="ihZjPtd" x1="2.75" x2="29.375" y1="20.063" y2="20.063" gradientUnits="userSpaceOnUse"><stop class="x6ov34adx"/><stop offset="1" class="stjqdpbnw"/></linearGradient><linearGradient id="iE4Mqzb" x1="4.938" x2="27.662" y1="19.059" y2="19.059" gradientUnits="userSpaceOnUse"><stop class="kfo23yoae"/><stop offset="1" class="o1pirpbcx"/></linearGradient><linearGradient id="i4HDmOc" x1="25.886" x2="6.39" y1="16.688" y2="16.875" gradientUnits="userSpaceOnUse"><stop class="xfyghdalm"/><stop offset=".501" class="iael4yldb"/><stop offset="1" class="vllvy2lch"/></linearGradient><linearGradient id="i0PEqzf" x1="23.554" x2="18.963" y1="16.297" y2="23.7" gradientUnits="userSpaceOnUse"><stop class="xmwvcbcvw"/><stop offset="1" class="d1kfutqkd"/></linearGradient><linearGradient id="iMuFJSd" x1="8.125" x2="8.125" y1="15.828" y2="24.453" gradientUnits="userSpaceOnUse"><stop offset=".471" class="ps312en5e"/><stop offset=".841" class="fcd09pbve"/></linearGradient><linearGradient id="iILrdcG" x1="13.928" x2="15.694" y1="7.818" y2="7.818" gradientUnits="userSpaceOnUse"><stop class="h2txlxb4n"/><stop offset=".251" class="ygc9nnbrb"/><stop offset=".496" class="j8za2e5lh"/><stop offset=".708" class="dyjd4l21l"/></linearGradient><linearGradient id="iJR246c" x1="15.918" x2="17.684" y1="9.332" y2="9.332" gradientUnits="userSpaceOnUse"><stop class="h2txlxb4n"/><stop offset=".251" class="ygc9nnbrb"/><stop offset=".496" class="j8za2e5lh"/><stop offset=".708" class="dyjd4l21l"/></linearGradient><linearGradient id="iUDTiOn" x1="17.938" x2="19.704" y1="6.483" y2="6.483" gradientUnits="userSpaceOnUse"><stop class="h2txlxb4n"/><stop offset=".251" class="ygc9nnbrb"/><stop offset=".496" class="j8za2e5lh"/><stop offset=".708" class="dyjd4l21l"/></linearGradient><filter id="iojEcyV" width="16.278" height="6.156" x="13.394" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".125"/></filter><filter id="ib2SmBL" width="28" height="16" x="1.875" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".25"/></filter><filter id="ipN8nRb" width="24.162" height="14.617" x="3.75" y="11.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".125"/></filter><filter id="i4SFY2d" width="20.552" height="11.078" x="5.834" y="13.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".25"/></filter><filter id="iZZs4qe" width="3.286" height="3.286" x="11.138" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".125"/></filter><filter id="iCoo9oc" width="3.286" height="3.286" x="17.664" y="17.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".125"/></filter><filter id="iPzv7cC" width="3.286" height="3.286" x="14.294" y="13.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".125"/></filter><filter id="iUdAqEd" width="7.088" height="7.719" x="18.625" y="15.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".25"/></filter><filter id="iBX4qWd" width="14.852" height="11.672" x="11.914" y="13.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".25"/></filter><filter id="iUCaPXc" width="15.281" height="11.547" x="5.219" y="13.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28413" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:spaghetti" /></template>
<style>
.adfwf0ayq {
  d: path("M5.719 19.328c0-2.692 1.922-4.89 3.781-5.422c-.854.365-3.328 1.796-3.328 5.422c0 1.89 2.406 4.906 5.547 4.906H20v.22h-8.281c-3.875 0-6-3.563-6-5.126");
}

.aj5600bwk {
  d: path("M22.01 12.328H10.02c-4.43 0-8.02 3.39-8.02 8.21c0 4.492 3.59 7.68 8.02 7.68h11.99c4.43 0 8.02-3.188 8.02-7.68c-.01-4.492-3.6-8.21-8.02-8.21");
}

.b5kunqbww {
  stop-color: var(--svg-color--888291, #888291);
}

.b8a0bvb3f {
  d: path("M29.422 4.563s-6.188.27-6.828.14s-1.422-2.094-3.985-2.094l-4.265-.28c-.41 0-.481.011-.481.421s.07.438.48.438h2.602c.414 0 .79.335.79.796s-.415.72-.79.72h-2.742c-.41 0-.481.042-.481.452s.071.469.481.469h2.742c.367 0 .79.219.79.695c0 .477-.368.696-.79.696h-2.82c-.41 0-.481.105-.481.515s.15.453.56.453h4.405c3.141 0 3.36-1.906 4.266-2c.906-.093 6.547 0 6.547 0z");
}

.d1kfutqkd {
  stop-color: var(--svg-color--f4c924, #F4C924);
}

.dyjd4l21l {
  stop-color: var(--svg-color--e8b83e, #E8B83E);
}

.eey99_bhz {
  stop-color: var(--svg-color--9f82ad, #9F82AD);
  stop-opacity: 0;
}

.ehc3c6bri {
  stop-color: var(--svg-color--80736f, #80736F);
}

.eihz2rbpj {
  stop-color: var(--svg-color--da9360, #DA9360);
}

.elzm1fbwf {
  d: path("M16.1 16.097a1.393 1.393 0 1 0 0-2.786a1.393 1.393 0 0 0 0 2.786");
}

.em5n3nbos {
  stop-color: var(--svg-color--9e8373, #9E8373);
  stop-opacity: 0;
}

.euyaskkzn {
  stop-color: var(--svg-color--9a56a5, #9A56A5);
}

.eztutqbym {
  stop-color: var(--svg-color--fff254, #FFF254);
  stop-opacity: 0;
}

.fcd09pbve {
  stop-color: var(--svg-color--d39a4a, #D39A4A);
}

.fe39-9boy {
  d: path("M19.445 20.08a1.415 1.415 0 1 0 0-2.83a1.415 1.415 0 0 0 0 2.83");
}

.fq32t0a9q {
  stop-color: var(--svg-color--793c4f, #793C4F);
}

.ft5dv1b6b {
  fill: none;
}

.fu8-bsboc {
  d: path("M29.906 4s-6.672-.058-7.312-.187C21.954 3.683 21.172 2 18.609 2H13.95c-.41 0-.75.34-.75.75s.34.813.75.813h2.995s.508-.04.508.421s-.508.422-.508.422H13.95c-.41 0-.75.34-.75.75s.34.75.75.75h2.995s.508-.062.508.414c0 .477-.508.414-.508.414H13.95c-.41 0-.75.387-.75.797s.34.766.75.766h4.66c3.14 0 3.312-1.813 4.218-1.906c.906-.094 7.078-.094 7.078-.094z");
}

.g3g7i3ydq {
  fill-rule: evenodd;
  d: path("M14.51 3.734a.5.5 0 0 1 .5.5v7.383c0 .149.076.383.076.383c-.266.234-.79.273-1.14.094c0 0 .064-.211.064-.375V4.234a.5.5 0 0 1 .5-.5");
}

.g8ku9uqgn {
  stop-color: var(--svg-color--9a98a5, #9A98A5);
}

.gahlekbea {
  stop-color: var(--svg-color--8f74a2, #8F74A2);
  stop-opacity: 0;
}

.gqsj52v9c {
  d: path("M8.688 17.793c0 3.11 3.68 4.428 7.343 4.426c3.633-.003 7.25-1.3 7.25-4.427c0-3.326-3.617-4.739-7.25-4.73c-3.664.01-7.343 1.471-7.343 4.73");
}

.h-5-hz00x {
  d: path("M20.59 29.91h-9.28c-4.56 0-7.28-3.26-7.28-7.28v-2.88h23.84v2.88c0 4.02-2.464 7.28-7.28 7.28");
}

.h2txlxb4n {
  stop-color: var(--svg-color--ba8c3d, #BA8C3D);
}

.hdmk_hbvo {
  stop-color: var(--svg-color--f8d640, #F8D640);
}

.he2380b3g {
  stop-color: var(--svg-color--9b6e66, #9B6E66);
}

.hf75rvuwe {
  d: path("M12.987 19.914a1.41 1.41 0 1 0 0-2.82a1.41 1.41 0 0 0 0 2.82");
}

.hrzqfp8ld {
  d: path("M16.1 11.781c-4.381 0-7.781 1.313-10.381 4.125c-3.52 3.798-.344 10.032 5.031 10.032h10.031c5.875 0 8.965-6.344 5.297-10.297c-2.61-2.813-6.047-3.86-9.978-3.86");
}

.huvm4e9pq {
  stop-color: var(--svg-color--b72733, #B72733);
}

.i9e54sb-f {
  d: path("M24.375 16.188c1.125 1.843 2.35 6.718-5.25 6.718c4.464-1.432 6.031-2.406 5.25-6.718");
}

.iael4yldb {
  stop-color: var(--svg-color--eab342, #EAB342);
}

.ioz-tabvp {
  fill: var(--svg-color--ad8e36, #AD8E36);
  d: path("M16.1 11.781c-4.381 0-7.781 1.313-10.381 4.125c-3.52 3.798-.344 10.032 5.031 10.032h10.031c5.875 0 8.965-6.344 5.297-10.297c-2.61-2.813-6.047-3.86-9.978-3.86");
}

.iss3dtg2x {
  stop-color: var(--svg-color--7e6c77, #7E6C77);
  stop-opacity: 0;
}

.j8za2e5lh {
  stop-color: var(--svg-color--ffd851, #FFD851);
}

.j97kxmblv {
  stop-color: var(--svg-color--d79963, #D79963);
  stop-opacity: 0;
}

.jlxj8cckj {
  fill-rule: evenodd;
  d: path("M18.52 1.688a.5.5 0 0 1 .5.5v9.671c0 .196.09.375.09.375c-.36.164-1.008.079-1.196-.156c0 0 .106-.148.106-.336V2.188a.5.5 0 0 1 .5-.5");
}

.kfo23yoae {
  stop-color: var(--svg-color--8e6e6c, #8E6E6C);
}

.khi6flbrh {
  d: path("M26.266 19.375c0-2.692-1.953-5.031-3.516-5.594c.854.365 3.281 1.968 3.281 5.594c0 1.89-2.196 4.86-5.336 4.86h-8.281v.218h8.28c3.876 0 5.572-3.515 5.572-5.078");
}

.l7n_cpb3w {
  stop-color: var(--svg-color--df2c66, #DF2C66);
}

.lb0wcwbqp {
  stop-color: var(--svg-color--a17269, #A17269);
}

.lsrjxdbyj {
  stop-color: var(--svg-color--f4f2ff, #F4F2FF);
}

.lvqk0nqky {
  stop-color: var(--svg-color--8e74a0, #8E74A0);
}

.mib97vbha {
  stop-color: var(--svg-color--ab85d4, #AB85D4);
}

.n35fembwl {
  stop-color: var(--svg-color--a68eaa, #A68EAA);
  stop-opacity: 0;
}

.n3j0clbkp {
  stop-color: var(--svg-color--6c2730, #6C2730);
}

.nba_7yb5n {
  d: path("M21.65 12.563H10.1c-4.267 0-7.725 3.2-7.725 7.75c0 4.24 3.458 7.25 7.725 7.25h11.55c4.267 0 7.725-3.01 7.725-7.25c-.01-4.24-3.468-7.75-7.725-7.75");
}

.ng50wy7rm {
  stop-color: var(--svg-color--aeadb3, #AEADB3);
}

.nioqxz-4b {
  stop-color: var(--svg-color--c8a0f5, #C8A0F5);
  stop-opacity: 0;
}

.nsr-ftbsg {
  stop-color: var(--svg-color--cecbd6, #CECBD6);
  stop-opacity: 0;
}

.o1e0fx-wd {
  stop-color: var(--svg-color--fff254, #FFF254);
}

.o1pirpbcx {
  stop-color: var(--svg-color--b8a46e, #B8A46E);
}

.o61sdac3w {
  stop-color: var(--svg-color--d92b83, #D92B83);
}

.p8f1q_bno {
  stop-color: var(--svg-color--ff6e9a, #FF6E9A);
}

.pgzs8yw1z {
  d: path("M23.031 14c1.66 1.415 2.77 3.782 1.75 6.219c-.427 1.022-2.111 2.383-5.047 2.812c-1.153.169-4.925.1-7.062.094c-1.563 0-2.911-.018-4.453-1.656c-1.75-1.86-1.172-4.063.687-6.969c-2.39 1.078-3.75 5.281-1.203 7.86c.855.864 2.203 1.718 4.969 1.718h7.062c3.063 0 5.058-1.707 5.844-3.625c1.01-2.465-.631-5.574-2.547-6.453");
}

.pp8dtty2m {
  fill: var(--svg-color--9b86b5, #9B86B5);
  d: path("M20.59 29.91h-9.28c-4.56 0-7.28-3.26-7.28-7.28v-2.88h23.84v2.88c0 4.02-2.464 7.28-7.28 7.28");
}

.ps312en5e {
  stop-color: var(--svg-color--af9345, #AF9345);
}

.pscv-abgd {
  fill: var(--svg-color--b61738, #B61738);
  d: path("M19.307 20.08a1.393 1.393 0 1 0 0-2.787a1.393 1.393 0 0 0 0 2.786");
}

.pv1204byr {
  stop-color: var(--svg-color--ae2e36, #AE2E36);
}

.pywz8_b9k {
  fill: var(--svg-color--b61738, #B61738);
  d: path("M12.781 19.914a1.393 1.393 0 1 0 0-2.786a1.393 1.393 0 0 0 0 2.786");
}

.q9pw6jbml {
  stop-color: var(--svg-color--b52833, #B52833);
  stop-opacity: 0;
}

.qy1gwjb9k {
  stop-color: var(--svg-color--bb2635, #BB2635);
  stop-opacity: 0;
}

.r3voajbgm {
  stop-color: var(--svg-color--ffeb4a, #FFEB4A);
}

.sijfm5c7g {
  stop-color: var(--svg-color--9c816c, #9C816C);
}

.skh2d796p {
  stop-color: var(--svg-color--ffef4f, #FFEF4F);
  stop-opacity: 0;
}

.sm03mgz8i {
  stop-color: var(--svg-color--7f7371, #7F7371);
  stop-opacity: 0;
}

.smna-rb4b {
  stop-color: var(--svg-color--7e6e77, #7E6E77);
  stop-opacity: 0;
}

.stjqdpbnw {
  stop-color: var(--svg-color--dfd5db, #DFD5DB);
}

.swi2z_sri {
  stop-color: var(--svg-color--ab85d4, #AB85D4);
  stop-opacity: 0;
}

.t327bcbwo {
  stop-color: var(--svg-color--7e6d77, #7E6D77);
}

.t7ticbb7k {
  stop-color: var(--svg-color--867680, #867680);
  stop-opacity: 0;
}

.uqwr-l9qe {
  stop-color: var(--svg-color--e7be4c, #E7BE4C);
}

.usqk13ums {
  stop-color: var(--svg-color--afaeb3, #AFAEB3);
}

.v2fe1msxm {
  d: path("M15.984 12c-4.426 0-7.86 1.309-10.486 4.114c-3.556 3.787-.348 10.003 5.081 10.003h10.133c5.934 0 9.055-6.326 5.35-10.268C23.426 13.044 19.954 12 15.983 12");
}

.vabrk7b0x {
  fill: var(--svg-color--b61738, #B61738);
  d: path("M15.938 16.097a1.393 1.393 0 1 0 0-2.786a1.393 1.393 0 0 0 0 2.786");
}

.vh43avbco {
  stop-color: var(--svg-color--9f83ad, #9F83AD);
}

.vk7uuyb3q {
  fill: var(--svg-color--bf2b3b, #BF2B3B);
  d: path("M8.688 17.793c0 3.11 3.68 4.428 7.343 4.426c3.633-.003 7.25-1.3 7.25-4.427c0-3.326-3.617-4.739-7.25-4.73c-3.664.01-7.343 1.471-7.343 4.73");
}

.vllvy2lch {
  stop-color: var(--svg-color--d5aa38, #D5AA38);
}

.wk94u01pc {
  fill: var(--svg-color--b5aabb, #B5AABB);
  d: path("M29.422 4.563s-6.188.27-6.828.14s-1.422-2.094-3.985-2.094l-4.265-.28c-.41 0-.481.011-.481.421s.07.438.48.438h2.602c.414 0 .79.335.79.796s-.415.72-.79.72h-2.742c-.41 0-.481.042-.481.452s.071.469.481.469h2.742c.367 0 .79.219.79.695c0 .477-.368.696-.79.696h-2.82c-.41 0-.481.105-.481.515s.15.453.56.453h4.405c3.141 0 3.36-1.906 4.266-2c.906-.093 6.547 0 6.547 0z");
}

.woe16jbzr {
  stop-color: var(--svg-color--bd8def, #BD8DEF);
}

.wwqfcw0le {
  fill-rule: evenodd;
  d: path("M16.5 6.031a.5.5 0 0 1 .5.5v5.14c0 .126.07.306.07.306c-.234.257-.898.25-1.133 0c0 0 .063-.18.063-.305v-5.14a.5.5 0 0 1 .5-.5");
}

.wxmbkqb0o {
  stop-color: var(--svg-color--b1b1b6, #B1B1B6);
}

.wzoz5-bzo {
  stop-color: var(--svg-color--85747f, #85747F);
}

.x6ov34adx {
  stop-color: var(--svg-color--bcb4c3, #BCB4C3);
}

.xbiw5hcif {
  stop-color: var(--svg-color--d8d4df, #D8D4DF);
}

.xfyghdalm {
  stop-color: var(--svg-color--ffeb59, #FFEB59);
}

.xkmxg0b0o {
  stop-color: var(--svg-color--da9260, #DA9260);
  stop-opacity: 0;
}

.xmwvcbcvw {
  stop-color: var(--svg-color--f6ce2c, #F6CE2C);
}

.xoj332bzf {
  stop-color: var(--svg-color--916561, #916561);
}

.ygc9nnbrb {
  stop-color: var(--svg-color--deb030, #DEB030);
}

</style>
