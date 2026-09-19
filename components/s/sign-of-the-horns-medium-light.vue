<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iixpHWc)"><path class="osofq2u7h"/><path fill="url(#i8MPzMQ)" class="y4-1d2c4y"/><path fill="url(#iiKHiFb)" class="y4-1d2c4y"/><path fill="url(#iMfG7Sb)" class="y4-1d2c4y"/></g><g filter="url(#iVXmxhb)" class="uzda2u_lt"><path class="expy_e2jm"/></g><g filter="url(#iROC3hN)"><path class="xrkl8sb5i"/></g><rect fill="url(#itSgqSc)" class="cmhxacczj"/><rect fill="url(#iIQKFEb)" class="cmhxacczj"/><rect fill="url(#iK7qiOe)" class="ds-2d_5in"/><g filter="url(#iGjC2Vd)"><rect fill="url(#ii1AXLB)" class="i_06lgnxn"/><rect fill="url(#i2SPDAc)" class="i_06lgnxn"/></g><rect fill="url(#ij9R6uO)" class="i_06lgnxn"/><rect fill="url(#ihD7Kje)" class="i_06lgnxn"/><rect fill="url(#iI53A4b)" class="i_06lgnxn"/><g filter="url(#ixw1kgM)"><rect fill="url(#i3NeehK)" class="ni34yd1rs"/></g><rect fill="url(#iN6BWQb)" class="ni34yd1rs"/><g filter="url(#iWBDy7c)"><path class="hxu8s5bgm"/></g><path fill="url(#iSgkDNe)" class="mjtfhbcqy"/><path fill="url(#iZeMDyd)" class="mjtfhbcqy"/><path fill="url(#iSgkDNe)" class="kfpmqob8s"/><path fill="url(#iZeMDyd)" class="kfpmqob8s"/><path fill="url(#iWpUKFe)" class="mjtfhbcqy"/><path fill="url(#iWpUKFe)" class="kfpmqob8s"/><g filter="url(#if3Gzrb)"><path stroke="url(#iOpzGZd)" class="ug4kk3b-j"/></g><path fill="url(#iqSMIAe)" class="nx4kwab_h"/><path fill="url(#io2wcuz)" class="nx4kwab_h"/><path fill="url(#io8twje)" class="nx4kwab_h"/><path fill="url(#iPKAJHb)" class="nx4kwab_h"/><g filter="url(#iDifYKe)"><path stroke="url(#iSroZvd)" class="yygeoqu1e"/></g><g filter="url(#iyaLgSQ)"><rect class="z_f1pgk1w"/></g><g filter="url(#iClIFDp)"><rect class="vva4b94kl"/></g><defs><radialGradient id="i8MPzMQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.40994 -4.40607 5.09243 1.62958 21.174 16.322)" gradientUnits="userSpaceOnUse"><stop class="uijsg0bca"/><stop offset="1" class="ndxnyxbdn"/></radialGradient><radialGradient id="iiKHiFb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26865 0 0 -4.94397 21.72 20.703)" gradientUnits="userSpaceOnUse"><stop class="p_tek44dc"/><stop offset="1" class="f-r86--gd"/></radialGradient><radialGradient id="iMfG7Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.59133 6.41699 -6.71794 -7.94735 11.579 15.759)" gradientUnits="userSpaceOnUse"><stop class="emiouyspp"/><stop offset="1" class="zy60p2y3w"/></radialGradient><radialGradient id="itSgqSc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.39062 3.59376 -2.77814 -2.6211 12.745 12.423)" gradientUnits="userSpaceOnUse"><stop class="f8e5adc6k"/><stop offset="1" class="rpjgasb1k"/></radialGradient><radialGradient id="iIQKFEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.85935 0 0 1.79633 10.211 7.442)" gradientUnits="userSpaceOnUse"><stop class="nf11v4bta"/><stop offset="1" class="lva61bb1u"/></radialGradient><radialGradient id="iK7qiOe" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 0 0 2.21875 24.11 3.821)" gradientUnits="userSpaceOnUse"><stop class="ec28fgbcc"/><stop offset="1" class="gz26b2w_t"/></radialGradient><radialGradient id="i2SPDAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31357 .85703 -1.14666 -1.7575 16.282 9.705)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="qoc7i_bco"/><stop offset="1" class="j2e_ep2zf"/></radialGradient><radialGradient id="ij9R6uO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.11578 6.51664 0 13.237 16.966)" gradientUnits="userSpaceOnUse"><stop class="nagre7w3q"/><stop offset="1" class="g6eo0uakq"/></radialGradient><radialGradient id="iI53A4b" cx="0" cy="0" r="1" gradientTransform="rotate(160.412 8.83 7.605)scale(9.71985 13.8653)" gradientUnits="userSpaceOnUse"><stop offset=".889" class="erbtdxupf"/><stop offset="1" class="hjdep4b4r"/></radialGradient><radialGradient id="iSgkDNe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10311 4.74572 -14.57712 -6.46 22.428 15.447)" gradientUnits="userSpaceOnUse"><stop class="nf7oq4oyk"/><stop offset="1" class="d0m3r-b7l"/></radialGradient><radialGradient id="iWpUKFe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.05883 0 0 -12.0286 20.946 16.554)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="qcq5g2bfi"/><stop offset="1" class="c4yf5rz9b"/></radialGradient><radialGradient id="io2wcuz" cx="0" cy="0" r="1" gradientTransform="matrix(22.82617 10.50104 -11.16142 24.26165 3.886 11.453)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="mo1liyikv"/><stop offset="1" class="lw0yy7c4u"/></radialGradient><radialGradient id="iPKAJHb" cx="0" cy="0" r="1" gradientTransform="rotate(100.422 4.715 12.679)scale(19.7254 14.941)" gradientUnits="userSpaceOnUse"><stop offset=".9" class="xwigb5gyl"/><stop offset="1" class="dgbq5tbtk"/></radialGradient><linearGradient id="ii1AXLB" x1="11.844" x2="14.864" y1="11.31" y2="11.319" gradientUnits="userSpaceOnUse"><stop class="x45arx2ti"/><stop offset="1" class="u-efnmtmj"/></linearGradient><linearGradient id="ihD7Kje" x1="15.398" x2="15.028" y1="12.665" y2="12.665" gradientUnits="userSpaceOnUse"><stop class="p7k_t-bxf"/><stop offset="1" class="qzpsak1fa"/></linearGradient><linearGradient id="i3NeehK" x1="16.302" x2="20.739" y1="10.396" y2="10.396" gradientUnits="userSpaceOnUse"><stop class="o9d55zgnu"/><stop offset="1" class="r6wimeb2r"/></linearGradient><linearGradient id="iN6BWQb" x1="21.593" x2="17.527" y1="11.254" y2="11.254" gradientUnits="userSpaceOnUse"><stop class="b_52qabdh"/><stop offset="1" class="bnk_u9lsc"/></linearGradient><linearGradient id="iZeMDyd" x1="24.642" x2="21.636" y1="22.447" y2="19.938" gradientUnits="userSpaceOnUse"><stop offset=".249" class="yxj8k0bhh"/><stop offset="1" class="wiy2-4bwd"/></linearGradient><linearGradient id="iOpzGZd" x1="18.073" x2="25.419" y1="16" y2="18.712" gradientUnits="userSpaceOnUse"><stop class="v1zrjbb4x"/><stop offset="1" class="fqj6ljwln"/></linearGradient><linearGradient id="iqSMIAe" x1="26.12" x2="23.557" y1="16.482" y2="16.482" gradientUnits="userSpaceOnUse"><stop class="kw2-00ebh"/><stop offset="1" class="c6fuudbvt"/></linearGradient><linearGradient id="io8twje" x1="6.006" x2="6.834" y1="16.51" y2="16.51" gradientUnits="userSpaceOnUse"><stop class="j8ma1t34g"/><stop offset="1" class="vl7pjz0hc"/></linearGradient><linearGradient id="iSroZvd" x1="10.116" x2="10.164" y1="8.017" y2="17.161" gradientUnits="userSpaceOnUse"><stop class="tjf589b-b"/><stop offset="1" class="d806njbex"/></linearGradient><filter id="iixpHWc" width="20.413" height="28.703" x="6.169" y="1.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6875 0 0 0 0 0.494936 0 0 0 0 0.372396 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2546"/></filter><filter id="iVXmxhb" width="14.875" height="9.703" x="11.52" y="13.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation="1"/></filter><filter id="iROC3hN" width="10.099" height="10.995" x="7.835" y="8.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation="1"/></filter><filter id="iGjC2Vd" width="6.145" height="8.953" x="10.54" y="7.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.592157 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2546"/></filter><filter id="ixw1kgM" width="6.082" height="11.031" x="15.407" y="6.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.490196 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2546"/></filter><filter id="iWBDy7c" width="5.5" height="19.063" x="20.777" y="1.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation="1"/></filter><filter id="if3Gzrb" width="11.654" height="8.746" x="15.623" y="13.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation=".85"/></filter><filter id="iDifYKe" width="3" height="9.736" x="7.983" y="6.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation=".5"/></filter><filter id="iyaLgSQ" width="2.851" height="5.453" x="12.812" y="10.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation=".5"/></filter><filter id="iClIFDp" width="3.367" height="6.626" x="17.727" y="7.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2546" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sign-of-the-horns-medium-light" /></template>
<style>
.b_52qabdh {
  stop-color: var(--svg-color--ffd0a7, #FFD0A7);
}

.bnk_u9lsc {
  stop-color: var(--svg-color--ffd0a7, #FFD0A7);
  stop-opacity: 0;
}

.c4yf5rz9b {
  stop-color: var(--svg-color--cb9178, #CB9178);
}

.c6fuudbvt {
  stop-color: var(--svg-color--f5c39e, #F5C39E);
  stop-opacity: 0;
}

.cmhxacczj {
  width: 5.332px;
  height: 11.813px;
  x: 6.169px;
  y: 5.423px;
  rx: 2.666px;
}

.d0m3r-b7l {
  stop-color: var(--svg-color--b7737b, #B7737B);
}

.d806njbex {
  stop-color: var(--svg-color--fbc9a4, #FBC9A4);
  stop-opacity: 0;
}

.dgbq5tbtk {
  stop-color: var(--svg-color--bd788b, #BD788B);
}

.ds-2d_5in {
  width: 5.332px;
  height: 15.453px;
  x: 20.094px;
  y: 1.782px;
  rx: 2.666px;
}

.ec28fgbcc {
  stop-color: var(--svg-color--ffd0a9, #FFD0A9);
}

.emiouyspp {
  stop-color: var(--svg-color--c6907b, #C6907B);
}

.erbtdxupf {
  stop-color: var(--svg-color--d79c82, #D79C82);
  stop-opacity: 0;
}

.expy_e2jm {
  d: path("M16.372 15.01a2.851 2.851 0 1 0 0 5.704h1.624c3.034 0 4.127 0 6.399-.256c0-3.5-2.836-5.443-6.336-5.448m-1.687 0h1.68Z");
}

.f-r86--gd {
  stop-color: var(--svg-color--f2b6a3, #F2B6A3);
  stop-opacity: 0;
}

.f8e5adc6k {
  stop-color: var(--svg-color--b2715d, #B2715D);
}

.fqj6ljwln {
  stop-color: var(--svg-color--ffcfab, #FFCFAB);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g6eo0uakq {
  stop-color: var(--svg-color--b16c73, #B16C73);
  stop-opacity: 0;
}

.gz26b2w_t {
  stop-color: var(--svg-color--ffd0a9, #FFD0A9);
  stop-opacity: 0;
}

.hjdep4b4r {
  stop-color: var(--svg-color--d79c82, #D79C82);
}

.hxu8s5bgm {
  stroke: var(--svg-color--ffd0a8, #FFD0A8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M23.527 4.36v13.563");
}

.i_06lgnxn {
  width: 5.395px;
  height: 8.203px;
  x: 10.54px;
  y: 8.563px;
  rx: 2.697px;
}

.j2e_ep2zf {
  stop-color: var(--svg-color--a7714b, #A7714B);
  stop-opacity: 0;
}

.j8ma1t34g {
  stop-color: var(--svg-color--dfa487, #DFA487);
}

.kfpmqob8s {
  d: path("M17.739 13.876h1.68Z");
}

.kw2-00ebh {
  stop-color: var(--svg-color--f5c39e, #F5C39E);
}

.lva61bb1u {
  stop-color: var(--svg-color--fbcaa3, #FBCAA3);
  stop-opacity: 0;
}

.lw0yy7c4u {
  stop-color: var(--svg-color--d6a797, #D6A797);
}

.mjtfhbcqy {
  d: path("M17.739 13.876a2.851 2.851 0 1 0 0 5.703h1.624a1 1 0 0 1 .743.44l2.471 3.652a1 1 0 0 0 1.745-.16l.937-2.141c.332-.759.543-1.586.38-2.398a6.346 6.346 0 0 0-6.213-5.096");
}

.mo1liyikv {
  stop-color: var(--svg-color--d6a797, #D6A797);
  stop-opacity: 0;
}

.nagre7w3q {
  stop-color: var(--svg-color--b57278, #B57278);
}

.ndxnyxbdn {
  stop-color: var(--svg-color--ffc9a0, #FFC9A0);
  stop-opacity: 0;
}

.nf11v4bta {
  stop-color: var(--svg-color--fbcaa3, #FBCAA3);
}

.nf7oq4oyk {
  stop-color: var(--svg-color--f5c398, #F5C398);
}

.ni34yd1rs {
  width: 5.332px;
  height: 10.281px;
  x: 15.407px;
  y: 6.954px;
  rx: 2.666px;
}

.nx4kwab_h {
  d: path("M22.76 1.782a2.666 2.666 0 0 0-2.666 2.666v3.434c.402.466.645 1.074.645 1.738v4.95a2.666 2.666 0 0 1-5.184.879a2.697 2.697 0 0 1-5.016-1.38v-2.808c0-.829.374-1.57.962-2.065V8.09a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.843h1.187c2.91-.29 5.907-1.328 8.157-4.547c1.89-3.046 1.648-6.09 1.457-7.875l-.02-.187a95 95 0 0 1-.258-2.826V4.448a2.666 2.666 0 0 0-2.666-2.666");
}

.o9d55zgnu {
  stop-color: var(--svg-color--cc9676, #CC9676);
}

.osofq2u7h {
  fill: var(--svg-color--e0a397, #E0A397);
  d: path("M22.76 1.782a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.089a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.843h1.187c2.91-.29 5.907-1.328 8.157-4.547c1.89-3.046 1.648-6.09 1.457-7.875l-.02-.187a95 95 0 0 1-.258-2.826V4.448a2.666 2.666 0 0 0-2.666-2.666");
}

.p_tek44dc {
  stop-color: var(--svg-color--f2b6a3, #F2B6A3);
}

.p7k_t-bxf {
  stop-color: var(--svg-color--c2865b, #C2865B);
}

.qcq5g2bfi {
  stop-color: var(--svg-color--cb9178, #CB9178);
  stop-opacity: 0;
}

.qoc7i_bco {
  stop-color: var(--svg-color--a7714b, #A7714B);
}

.qzpsak1fa {
  stop-color: var(--svg-color--c2865b, #C2865B);
  stop-opacity: 0;
}

.r6wimeb2r {
  stop-color: var(--svg-color--f0c097, #F0C097);
}

.rpjgasb1k {
  stop-color: var(--svg-color--b2715d, #B2715D);
  stop-opacity: 0;
}

.tjf589b-b {
  stop-color: var(--svg-color--fbc9a4, #FBC9A4);
}

.u-efnmtmj {
  stop-color: var(--svg-color--ddaf8b, #DDAF8B);
}

.ug4kk3b-j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.073 16h2.834a3 3 0 0 1 2.613 1.527l1.307 2.318");
}

.uijsg0bca {
  stop-color: var(--svg-color--ffc9a0, #FFC9A0);
}

.uzda2u_lt {
  fill: var(--svg-color--a96766, #A96766);
}

.v1zrjbb4x {
  stop-color: var(--svg-color--ffcfab, #FFCFAB);
}

.vl7pjz0hc {
  stop-color: var(--svg-color--dfa487, #DFA487);
  stop-opacity: 0;
}

.vva4b94kl {
  width: 1.367px;
  height: 4.626px;
  x: 18.727px;
  y: 8.747px;
  fill: var(--svg-color--ffcfa5, #FFCFA5);
  rx: 0.684px;
}

.wiy2-4bwd {
  stop-color: var(--svg-color--d69d8a, #D69D8A);
  stop-opacity: 0;
}

.x45arx2ti {
  stop-color: var(--svg-color--d2a07d, #D2A07D);
}

.xrkl8sb5i {
  fill: var(--svg-color--a96766, #A96766);
  d: path("M9.835 10.717h6.099v6.995H9.835z");
}

.xwigb5gyl {
  stop-color: var(--svg-color--bd788b, #BD788B);
  stop-opacity: 0;
}

.y4-1d2c4y {
  d: path("M22.76 1.782a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.089a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.843h1.187c2.91-.29 5.907-1.328 8.157-4.547c1.89-3.046 1.648-6.09 1.457-7.875l-.02-.187a95 95 0 0 1-.258-2.826V4.448a2.666 2.666 0 0 0-2.666-2.666");
}

.yxj8k0bhh {
  stop-color: var(--svg-color--d69d8a, #D69D8A);
}

.yygeoqu1e {
  stroke-linecap: round;
  d: path("M9.483 8.333v6.736");
}

.z_f1pgk1w {
  width: 0.851px;
  height: 3.453px;
  x: 13.812px;
  y: 11.154px;
  fill: var(--svg-color--f2c1a2, #F2C1A2);
  rx: 0.426px;
}

.zy60p2y3w {
  stop-color: var(--svg-color--c6907b, #C6907B);
  stop-opacity: 0;
}

</style>
