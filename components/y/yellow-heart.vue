<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iB3D1Vb)" class="husyw_bka"/><path fill="url(#iVp2DLb)" class="husyw_bka"/><path fill="url(#iAUo06b)" class="husyw_bka"/><path fill="url(#i2IJ7Od)" class="husyw_bka"/><path fill="url(#iyyN8nc)" class="husyw_bka"/><path fill="url(#iyX9l5d)" class="husyw_bka"/><path fill="url(#i611u0d)" class="husyw_bka"/><path fill="url(#iSqxTCe)" class="husyw_bka"/><path fill="url(#iUmZwJe)" class="x7bh3ubrn"/><path fill="url(#itxrUSd)" class="oi_9zmb4g"/><path fill="url(#iDkSLZd)" class="oi_9zmb4g"/><g filter="url(#iHjdYAd)"><path fill="url(#ixESTGP)" class="b42iqhbgi"/></g><g filter="url(#i64Eccd)"><ellipse fill="url(#i5JJabc)" transform="rotate(-.697 9.263 6.289)" class="jausm9biz"/></g><g filter="url(#iTaIr4c)"><path fill="url(#iHF2AVd)" class="by94wtjws"/></g><g filter="url(#izHTkCb)"><ellipse fill="url(#ix7BJsc)" class="dv8-fmcnu"/></g><g filter="url(#ippkF2v)"><path class="cami6obdf"/></g><g filter="url(#iYYqQpg)"><path class="huairgb6l"/></g><defs><radialGradient id="iB3D1Vb" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.5 -58.948 0 14.887 9.752)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="r-8jnbbhh"/><stop offset="1" class="gmelrdffb"/></radialGradient><radialGradient id="iVp2DLb" cx="0" cy="0" r="1" gradientTransform="rotate(116.407 9.623 12.067)scale(10.1182 9.41358)" gradientUnits="userSpaceOnUse"><stop class="r-8jnbbhh"/><stop offset="1" class="gd4jr8kgh"/></radialGradient><radialGradient id="i2IJ7Od" cx="0" cy="0" r="1" gradientTransform="rotate(129.54 8.745 11.064)scale(22.7917 42.6912)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="j1afgmb0t"/><stop offset=".908" class="yfa4qab2b"/></radialGradient><radialGradient id="iyyN8nc" cx="0" cy="0" r="1" gradientTransform="matrix(-20.12496 -9.75003 11.86302 -24.48637 17.335 17.627)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="ftz4i9b0y"/><stop offset="1" class="lqfzg2bol"/></radialGradient><radialGradient id="iyX9l5d" cx="0" cy="0" r="1" gradientTransform="rotate(-152.113 10.856 6.662)scale(18.1729 16.0734)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="ftz4i9b0y"/><stop offset="1" class="lqfzg2bol"/></radialGradient><radialGradient id="i611u0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.7992 -26.4278 0 15.38 13.816)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="j1afgmb0t"/><stop offset=".934" class="yfa4qab2b"/></radialGradient><radialGradient id="iSqxTCe" cx="0" cy="0" r="1" gradientTransform="matrix(16.87497 16.4375 -45.77958 46.99799 10.273 9.377)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="j1afgmb0t"/><stop offset="1" class="yfa4qab2b"/></radialGradient><radialGradient id="itxrUSd" cx="0" cy="0" r="1" gradientTransform="matrix(7.31249 -12.5 11.72334 6.85814 21.808 15.556)" gradientUnits="userSpaceOnUse"><stop offset=".672" class="m5pf26p0a"/><stop offset="1" class="h0g4r9bmv"/></radialGradient><radialGradient id="iDkSLZd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.81254 -7.9931 8.12584 -6.92566 23.87 12.993)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="g6iijsxrh"/><stop offset=".906" class="nwam5nqnx"/></radialGradient><radialGradient id="ixESTGP" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.6875 -5.77863 0 18.436 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="zsp3cvz6t"/><stop offset="1" class="prnil8vbk"/></radialGradient><radialGradient id="i5JJabc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.0437 -.29688 .12231 -1.66597 12.823 6.149)" gradientUnits="userSpaceOnUse"><stop class="zaigj4bqx"/><stop offset="1" class="lb5l0hb7w"/></radialGradient><radialGradient id="iHF2AVd" cx="0" cy="0" r="1" gradientTransform="matrix(-9.6251 -9.43744 26.61742 -27.14668 19.835 10.002)" gradientUnits="userSpaceOnUse"><stop class="zaigj4bqx"/><stop offset="1" class="lb5l0hb7w"/></radialGradient><radialGradient id="ix7BJsc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.73797 6.33775 -10.19904 -7.62458 25.834 6.707)" gradientUnits="userSpaceOnUse"><stop class="zaigj4bqx"/><stop offset="1" class="lb5l0hb7w"/></radialGradient><filter id="iHjdYAd" width="9.902" height="16.759" x="13.166" y="6.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7319_6105" stdDeviation="1.5"/></filter><filter id="i64Eccd" width="6.037" height="3.5" x="6.245" y="4.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7319_6105" stdDeviation=".75"/></filter><filter id="iTaIr4c" width="13.229" height="21.857" x="4.748" y="3.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7319_6105" stdDeviation="1.5"/></filter><filter id="izHTkCb" width="16.653" height="17.481" x="14.89" y="3.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7319_6105" stdDeviation="1.5"/></filter><filter id="ippkF2v" width="15.563" height="17" x="14.772" y="11.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7319_6105" stdDeviation="1.5"/></filter><filter id="iYYqQpg" width="17.25" height="19.125" x="1.022" y="9.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7319_6105" stdDeviation="1.5"/></filter><linearGradient id="iAUo06b" x1="13.62" x2="4.62" y1="16.346" y2="26.033" gradientUnits="userSpaceOnUse"><stop offset=".402" class="r_96yibrf"/><stop offset="1" class="gxm3k4byi"/></linearGradient><linearGradient id="iUmZwJe" x1="16.523" x2="14.887" y1="13.002" y2="29.939" gradientUnits="userSpaceOnUse"><stop offset=".512" class="qudiit10p"/><stop offset=".934" class="nm9aofbai"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yellow-heart" /></template>
<style>
.b42iqhbgi {
  d: path("M16.166 10.478v8.819c0 1.038 1.4 1.395 1.866.468c1.453-2.888 2.663-6.074 1.678-8.326c-.826-1.887-2.055-2.093-3.017-1.777c-.34.112-.527.458-.527.816");
}

.by94wtjws {
  d: path("m14.665 9.314l.313 13.063C8.101 15.689 6.262 7.868 8.897 6.814c2.634-1.053 5.017.938 5.767 2.5");
}

.cami6obdf {
  stroke: var(--svg-color--ffc037, #FFC037);
  stroke-linecap: round;
  d: path("M26.835 15.127c-1.062 2.562-5.437 7.937-8.562 10");
}

.dv8-fmcnu {
  cx: 23.216px;
  cy: 12.447px;
  rx: 5.327px;
  ry: 5.74px;
}

.ft5dv1b6b {
  fill: none;
}

.ftz4i9b0y {
  stop-color: var(--svg-color--9b7c23, #9B7C23);
  stop-opacity: 0;
}

.g6iijsxrh {
  stop-color: var(--svg-color--c5a34c, #C5A34C);
  stop-opacity: 0;
}

.gd4jr8kgh {
  stop-color: var(--svg-color--ffd765, #FFD765);
  stop-opacity: 0;
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gxm3k4byi {
  stop-color: var(--svg-color--ed7839, #ED7839);
}

.h0g4r9bmv {
  stop-color: var(--svg-color--fea16f, #FEA16F);
}

.huairgb6l {
  stroke: var(--svg-color--faa730, #FAA730);
  stroke-linecap: round;
  d: path("M4.522 13.252c1.188 5.5 7.126 10.062 10.25 12.125");
}

.husyw_bka {
  d: path("M15.037 29.202a1.73 1.73 0 0 0 1.71-.023c3.583-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.025-1.898 1.542c-.237.234-.656.258-.903.034c-.691-.63-1.771-1.436-2.465-1.905c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.109 12.476");
}

.j1afgmb0t {
  stop-color: var(--svg-color--ff69cf, #FF69CF);
  stop-opacity: 0;
}

.jausm9biz {
  cx: 9.263px;
  cy: 6.289px;
  rx: 1.519px;
  ry: 0.249px;
}

.lb5l0hb7w {
  stop-color: var(--svg-color--ffe647, #FFE647);
  stop-opacity: 0;
}

.lqfzg2bol {
  stop-color: var(--svg-color--9b7c23, #9B7C23);
}

.m5pf26p0a {
  stop-color: var(--svg-color--f9861d, #F9861D);
  stop-opacity: 0;
}

.nm9aofbai {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
}

.nwam5nqnx {
  stop-color: var(--svg-color--c5a34c, #C5A34C);
}

.oi_9zmb4g {
  d: path("m15.535 8.107l.004.004c.247.224.666.2.903-.034c.396-.389.925-.794 1.422-1.175q.248-.188.476-.366c5.824-4.578 14.251 1.786 10.662 9.759a18.8 18.8 0 0 1-1.863 3.485z");
}

.prnil8vbk {
  stop-color: var(--svg-color--ffbf2b, #FFBF2B);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r_96yibrf {
  stop-color: var(--svg-color--ed7839, #ED7839);
  stop-opacity: 0;
}

.r-8jnbbhh {
  stop-color: var(--svg-color--ffd765, #FFD765);
}

.x7bh3ubrn {
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("M15.037 29.202a1.73 1.73 0 0 0 1.71-.023c3.583-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.025-1.898 1.542c-.237.234-.656.258-.903.034c-.691-.63-1.771-1.436-2.465-1.905c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.109 12.476");
}

.yfa4qab2b {
  stop-color: var(--svg-color--ff69cf, #FF69CF);
}

.zaigj4bqx {
  stop-color: var(--svg-color--ffe647, #FFE647);
}

.zsp3cvz6t {
  stop-color: var(--svg-color--ffbf2b, #FFBF2B);
}

</style>
