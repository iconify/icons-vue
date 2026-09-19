<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="k0voktrza"/><path fill="url(#iarxoxM)" class="d60hfbc0a"/><path fill="url(#iIqwS2b)" class="d60hfbc0a"/><path fill="url(#iHq6Lmd)" class="d60hfbc0a"/><path fill="url(#ixrsANb)" class="d60hfbc0a"/><path fill="url(#inqPYbc)" class="d60hfbc0a"/><path fill="url(#iS6bu8b)" class="wiughxbis"/><path fill="url(#iD1rC5k)" class="wiughxbis"/><path fill="url(#iF8701H)" class="jg-7_31so"/><g filter="url(#inaTWFk)"><path class="ocetncbto"/></g><path fill="url(#igtAB7d)" class="vb1v_abhv"/><path fill="url(#ioJ2Upc)" class="vb1v_abhv"/><path fill="url(#iw5rAhe)" class="vb1v_abhv"/><path fill="url(#iueF5zb)" class="fmlp9jf5f"/><path fill="url(#iNhDRzd)" class="fmlp9jf5f"/><g filter="url(#iEV4G2c)"><path fill="url(#i97IQBe)" class="mgglu2kwl"/><path fill="url(#i80DXzc)" class="mgglu2kwl"/><path fill="url(#iiC5wxd)" class="mgglu2kwl"/></g><g filter="url(#iAvF89c)"><circle stroke="url(#iubRtab)" class="pukzrdpdd"/></g><circle fill="url(#iuv0lOd)" class="mnolkfbid"/><circle fill="url(#iaELXac)" class="mnolkfbid"/><g filter="url(#iluC8Kc)"><circle stroke="url(#izv4p3c)" class="x3z5grzma"/></g><circle fill="url(#iBeTLie)" class="rsiapj44o"/><circle fill="url(#ilYmPpd)" class="rsiapj44o"/><g filter="url(#ivvGiZW)"><circle stroke="url(#i3Jm8Xb)" class="arkz-0bty"/></g><circle fill="url(#iLDd6kx)" class="s318vybyc"/><circle fill="url(#iAsfRii)" class="s318vybyc"/><g filter="url(#iIe8vWd)"><path stroke="url(#ii4JQXd)" class="ql4p7ubub"/></g><g filter="url(#iZ4uA1g)"><path stroke="url(#iv94hGc)" class="wrbas5bxk"/></g><defs><linearGradient id="inqPYbc" x1="3.775" x2="7.4" y1="18.281" y2="18.281" gradientUnits="userSpaceOnUse"><stop class="hx5mfubpc"/><stop offset="1" class="ol1cs92sk"/></linearGradient><linearGradient id="iS6bu8b" x1="10.961" x2="10.961" y1="7.719" y2="16" gradientUnits="userSpaceOnUse"><stop class="eltyy8bcx"/><stop offset="1" class="gfg-7tbjl"/></linearGradient><linearGradient id="iF8701H" x1="22.42" x2="22.42" y1="8.625" y2="30.184" gradientUnits="userSpaceOnUse"><stop class="hdlafp84a"/><stop offset="1" class="v6xlr7u-t"/></linearGradient><linearGradient id="igtAB7d" x1="7.282" x2="7.282" y1="30.406" y2="29.523" gradientUnits="userSpaceOnUse"><stop offset=".1" class="gcfkwobwb"/><stop offset="1" class="lot-b7k1g"/></linearGradient><linearGradient id="iw5rAhe" x1="9.275" x2="8.807" y1="15.906" y2="16.656" gradientUnits="userSpaceOnUse"><stop offset=".21" class="m-lck8b6v"/><stop offset="1" class="r2gwqrbcb"/></linearGradient><linearGradient id="iueF5zb" x1="13.054" x2="13.054" y1="23.625" y2="30.206" gradientUnits="userSpaceOnUse"><stop class="mii75abid"/><stop offset="1" class="et-q2ibey"/></linearGradient><linearGradient id="iNhDRzd" x1="14.119" x2="14.119" y1="30.206" y2="29.797" gradientUnits="userSpaceOnUse"><stop class="cj0m3qbna"/><stop offset="1" class="l0vuudriw"/></linearGradient><linearGradient id="i97IQBe" x1="16" x2="16" y1="22.167" y2="30.206" gradientUnits="userSpaceOnUse"><stop class="g6gnpxb-s"/><stop offset="1" class="qqzqngg1v"/></linearGradient><linearGradient id="i80DXzc" x1="19.159" x2="17.394" y1="27.201" y2="28.177" gradientUnits="userSpaceOnUse"><stop offset=".171" class="bfu4ykbbs"/><stop offset="1" class="xcr5l94qu"/></linearGradient><linearGradient id="iiC5wxd" x1="17.065" x2="17.065" y1="30.206" y2="29.988" gradientUnits="userSpaceOnUse"><stop class="rxyj61bqy"/><stop offset="1" class="ljt23lbjo"/><stop offset="1" class="l0vuudriw"/></linearGradient><linearGradient id="iubRtab" x1="14.525" x2="16.408" y1="29.172" y2="27.359" gradientUnits="userSpaceOnUse"><stop offset=".343" class="a4_y8vbcu"/><stop offset="1" class="h94vvnbji"/></linearGradient><linearGradient id="izv4p3c" x1="15.316" x2="16.51" y1="26.23" y2="25.081" gradientUnits="userSpaceOnUse"><stop offset=".343" class="a4_y8vbcu"/><stop offset="1" class="h94vvnbji"/></linearGradient><linearGradient id="i3Jm8Xb" x1="16.992" x2="17.635" y1="27.571" y2="26.952" gradientUnits="userSpaceOnUse"><stop offset=".343" class="a4_y8vbcu"/><stop offset="1" class="h94vvnbji"/></linearGradient><linearGradient id="ii4JQXd" x1="6.4" x2="8.979" y1="15.953" y2="16.766" gradientUnits="userSpaceOnUse"><stop offset=".334" class="djw8_7bza"/><stop offset="1" class="tl39k_btt"/></linearGradient><linearGradient id="iv94hGc" x1="8.883" x2="10.745" y1="17.031" y2="17.321" gradientUnits="userSpaceOnUse"><stop class="djw8_7bza"/><stop offset="1" class="tl39k_btt"/></linearGradient><radialGradient id="iarxoxM" cx="0" cy="0" r="1" gradientTransform="matrix(3.6172 -4.875 7.9128 5.87121 10.15 26.031)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="kr149kbfb"/><stop offset="1" class="qw5yy2b2j"/></radialGradient><radialGradient id="iIqwS2b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99996 -5.89848 10.54369 -12.5126 24.463 30.18)" gradientUnits="userSpaceOnUse"><stop class="r9d6ar69f"/><stop offset="1" class="v5k_l_bvq"/></radialGradient><radialGradient id="iHq6Lmd" cx="0" cy="0" r="1" gradientTransform="rotate(-147.619 19.189 13.234)scale(18.2059 4.30025)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="ivqi8gb6q"/><stop offset="1" class="ylp6k5b2f"/></radialGradient><radialGradient id="ixrsANb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.03125 1.375 0 10.9 26.813)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="a8ab_8b_d"/><stop offset="1" class="pptbmdbim"/></radialGradient><radialGradient id="iD1rC5k" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 -.53906 .42943 -.74683 5.314 16)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="k4eqg2b5b"/><stop offset="1" class="oqb0mpb-t"/></radialGradient><radialGradient id="ioJ2Upc" cx="0" cy="0" r="1" gradientTransform="matrix(-.88451 -1.13282 .57457 -.44863 6.01 17.586)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="u4826qbwh"/><stop offset="1" class="lxpl-bbvv"/></radialGradient><radialGradient id="iuv0lOd" cx="0" cy="0" r="1" gradientTransform="rotate(-26.281 68.848 -17.085)scale(1.41154)" gradientUnits="userSpaceOnUse"><stop class="nw0tc8bsr"/><stop offset="1" class="v5n654s4w"/></radialGradient><radialGradient id="iaELXac" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .82031 -1.90911 1.23638 14.525 27.133)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="udaqdrx6v"/><stop offset="1" class="di-lu9b9d"/></radialGradient><radialGradient id="iBeTLie" cx="0" cy="0" r="1" gradientTransform="rotate(-26.281 63.27 -20.044)scale(.89463)" gradientUnits="userSpaceOnUse"><stop class="nw0tc8bsr"/><stop offset="1" class="v5n654s4w"/></radialGradient><radialGradient id="ilYmPpd" cx="0" cy="0" r="1" gradientTransform="matrix(.3367 .51992 -1.21 .78362 15.316 24.938)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="udaqdrx6v"/><stop offset="1" class="di-lu9b9d"/></radialGradient><radialGradient id="iLDd6kx" cx="0" cy="0" r="1" gradientTransform="rotate(-26.282 67.242 -22.797)scale(.48211)" gradientUnits="userSpaceOnUse"><stop class="nw0tc8bsr"/><stop offset="1" class="v5n654s4w"/></radialGradient><radialGradient id="iAsfRii" cx="0" cy="0" r="1" gradientTransform="matrix(.18145 .28018 -.65206 .42229 16.992 26.875)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="udaqdrx6v"/><stop offset="1" class="di-lu9b9d"/></radialGradient><filter id="inaTWFk" width="4.963" height="15.317" x="5.125" y="14.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.588235 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25971"/></filter><filter id="iEV4G2c" width="7.383" height="8.039" x="12.283" y="22.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.913725 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25971"/></filter><filter id="iAvF89c" width="2.419" height="2.419" x="14.089" y="27.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25971" stdDeviation=".025"/></filter><filter id="iluC8Kc" width="1.606" height="1.606" x="15.004" y="24.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25971" stdDeviation=".025"/></filter><filter id="ivvGiZW" width=".958" height=".958" x="16.777" y="26.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25971" stdDeviation=".025"/></filter><filter id="iIe8vWd" width="3.263" height="2.325" x="5.707" y="15.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25971" stdDeviation=".2"/></filter><filter id="iZ4uA1g" width="1.2" height="13.45" x="6.988" y="16.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25971" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mouse-trap" /></template>
<style>
.a4_y8vbcu {
  stop-color: var(--svg-color--fff064, #FFF064);
}

.a8ab_8b_d {
  stop-color: var(--svg-color--47211e, #47211E);
}

.arkz-0bty {
  cx: 17.256px;
  cy: 27.254px;
  r: 0.379px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.bfu4ykbbs {
  stop-color: var(--svg-color--ffd152, #FFD152);
}

.cj0m3qbna {
  stop-color: var(--svg-color--e26675, #E26675);
}

.d60hfbc0a {
  d: path("M2.26 16h12.28l10.734 14.18H13.15z");
}

.di-lu9b9d {
  stop-color: var(--svg-color--d78134, #D78134);
  stop-opacity: 0;
}

.djw8_7bza {
  stop-color: var(--svg-color--e4dee8, #E4DEE8);
}

.eltyy8bcx {
  stop-color: var(--svg-color--facc8d, #FACC8D);
}

.et-q2ibey {
  stop-color: var(--svg-color--f48543, #F48543);
}

.fmlp9jf5f {
  d: path("M16 22.155v5.66l.671 1.553a.6.6 0 0 1-.55.838H9.987a.6.6 0 0 1-.548-.844l2.851-6.73a.8.8 0 0 1 .695-.475v-.002z");
}

.ft5dv1b6b {
  fill: none;
}

.g6gnpxb-s {
  stop-color: var(--svg-color--ffdc53, #FFDC53);
}

.gcfkwobwb {
  stop-color: var(--svg-color--9f69cb, #9F69CB);
}

.gfg-7tbjl {
  stop-color: var(--svg-color--ca7e35, #CA7E35);
}

.h94vvnbji {
  stop-color: var(--svg-color--ecaf4b, #ECAF4B);
}

.hdlafp84a {
  stop-color: var(--svg-color--ffecae, #FFECAE);
}

.hx5mfubpc {
  stop-color: var(--svg-color--42201f, #42201F);
}

.ivqi8gb6q {
  stop-color: var(--svg-color--975041, #975041);
  stop-opacity: 0.937;
}

.jg-7_31so {
  d: path("M29.904 22.797a2.5 2.5 0 0 0-.135-2.844L20.236 7.498a.35.35 0 0 0-.577.032L14.557 16l10.73 14.184z");
}

.k0voktrza {
  fill: var(--svg-color--ffd68a, #FFD68A);
  d: path("M20.26 7.523a1.3 1.3 0 0 0-.93-.445l-.187.91l.437.32z");
}

.k4eqg2b5b {
  stop-color: var(--svg-color--814c25, #814C25);
}

.kr149kbfb {
  stop-color: var(--svg-color--6c3b31, #6C3B31);
}

.l0vuudriw {
  stop-color: var(--svg-color--f48a40, #F48A40);
  stop-opacity: 0;
}

.ljt23lbjo {
  stop-color: var(--svg-color--ffda54, #FFDA54);
  stop-opacity: 0;
}

.lot-b7k1g {
  stop-color: var(--svg-color--af93ca, #AF93CA);
  stop-opacity: 0;
}

.lxpl-bbvv {
  stop-color: var(--svg-color--9e8eae, #9E8EAE);
  stop-opacity: 0;
}

.m-lck8b6v {
  stop-color: var(--svg-color--7b5f7d, #7B5F7D);
}

.mgglu2kwl {
  d: path("m16.69 22.59l2.927 6.778a.6.6 0 0 1-.551.838h-6.132a.6.6 0 0 1-.548-.844l3.021-6.78a.7.7 0 0 1 1.282.008");
}

.mii75abid {
  stop-color: var(--svg-color--e9bb15, #E9BB15);
}

.mnolkfbid {
  cx: 15.299px;
  cy: 28.242px;
  r: 1.109px;
}

.nw0tc8bsr {
  stop-color: var(--svg-color--ffbe50, #FFBE50);
}

.ocetncbto {
  fill: var(--svg-color--d2c6db, #D2C6DB);
  d: path("M7.434 16a.4.4 0 0 1-.112.014a.34.34 0 0 1-.154-.031a.4.4 0 0 1-.11-.088a.7.7 0 0 1-.151-.29a.9.9 0 1 0-1.763.368c.066.316.24.747.568 1.117q.178.203.422.37c.2.133.35.345.35.586v11.36a.8.8 0 0 0 1.6 0V18.1c0-.25.16-.467.37-.603c.614-.397.855-1.048.923-1.231l.007-.019A1 1 0 0 0 9.439 16z");
}

.ol1cs92sk {
  stop-color: var(--svg-color--42201f, #42201F);
  stop-opacity: 0;
}

.oqb0mpb-t {
  stop-color: var(--svg-color--d0873f, #D0873F);
  stop-opacity: 0;
}

.pptbmdbim {
  stop-color: var(--svg-color--47211e, #47211E);
  stop-opacity: 0;
}

.pukzrdpdd {
  cx: 15.299px;
  cy: 28.242px;
  r: 1.109px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ql4p7ubub {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.307 15.64c.041.376.337 1.126 1.187 1.126c.6 0 .833-.271.875-.407");
}

.qqzqngg1v {
  stop-color: var(--svg-color--ffd954, #FFD954);
}

.qw5yy2b2j {
  stop-color: var(--svg-color--3a0a11, #3A0A11);
}

.r2gwqrbcb {
  stop-color: var(--svg-color--a897ab, #A897AB);
  stop-opacity: 0;
}

.r9d6ar69f {
  stop-color: var(--svg-color--561919, #561919);
}

.rsiapj44o {
  cx: 15.807px;
  cy: 25.641px;
  r: 0.703px;
}

.rxyj61bqy {
  stop-color: var(--svg-color--f9ba5a, #F9BA5A);
}

.s318vybyc {
  cx: 17.256px;
  cy: 27.254px;
  r: 0.379px;
}

.tl39k_btt {
  stop-color: var(--svg-color--e4dee8, #E4DEE8);
  stop-opacity: 0;
}

.u4826qbwh {
  stop-color: var(--svg-color--83669b, #83669B);
}

.udaqdrx6v {
  stop-color: var(--svg-color--d78134, #D78134);
}

.v5k_l_bvq {
  stop-color: var(--svg-color--561919, #561919);
  stop-opacity: 0;
}

.v5n654s4w {
  stop-color: var(--svg-color--c67a31, #C67A31);
}

.v6xlr7u-t {
  stop-color: var(--svg-color--ea9a60, #EA9A60);
}

.vb1v_abhv {
  d: path("M7.434 16a.4.4 0 0 1-.112.014a.34.34 0 0 1-.154-.031a.4.4 0 0 1-.11-.088a.7.7 0 0 1-.151-.29a.9.9 0 1 0-1.763.368c.066.316.24.747.568 1.117q.178.203.422.37c.2.133.35.345.35.586v11.36a.8.8 0 0 0 1.6 0V18.1c0-.25.16-.467.37-.603c.614-.397.855-1.048.923-1.231l.007-.019A1 1 0 0 0 9.439 16z");
}

.wiughxbis {
  d: path("M7.343 7.562a1 1 0 0 1 .857-.484h11.112a.35.35 0 0 1 .3.53L14.557 16H2.26z");
}

.wrbas5bxk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.588 17.031v12.25");
}

.x3z5grzma {
  cx: 15.807px;
  cy: 25.641px;
  r: 0.703px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.xcr5l94qu {
  stop-color: var(--svg-color--ffd152, #FFD152);
  stop-opacity: 0;
}

.ylp6k5b2f {
  stop-color: var(--svg-color--410e14, #410E14);
  stop-opacity: 0;
}

</style>
