<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irAlbbe)" class="jgs9rpm3b"/><path fill="url(#iGz8xxw)" class="jgs9rpm3b"/><path fill="url(#iG1YDhb)" class="jgs9rpm3b"/><path fill="url(#iKLbJAe)" class="qk2s94bex"/><path fill="url(#iS5Q45c)" class="qk2s94bex"/><path fill="url(#iwGUgtc)" class="qk2s94bex"/><path fill="url(#iXvDIOd)" class="qk2s94bex"/><path fill="url(#i9kko1c)" class="qk2s94bex"/><path fill="url(#iCfngnd)" class="qk2s94bex"/><path fill="url(#i64TQvc)" class="smdbqjopz"/><path fill="url(#iUkIIed)" class="smdbqjopz"/><path class="dj7v9n8vp"/><path fill="url(#iqiCy3c)" class="gcr3ehbfv"/><path fill="url(#iHp8fwc)" class="gcr3ehbfv"/><path fill="url(#iIRgz8d)" class="gcr3ehbfv"/><path fill="url(#ifVzuce)" class="gcr3ehbfv"/><path fill="url(#iXwOqde)" class="gcr3ehbfv"/><path fill="url(#iRWZhmb)" class="gcr3ehbfv"/><path fill="url(#iLAFqob)" class="wl4ju0bqw"/><defs><radialGradient id="iG1YDhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.6175 -11.1615 0 16.08 13.563)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="tvicpkgom"/><stop offset=".866" class="ct58cdbwd"/></radialGradient><radialGradient id="iS5Q45c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.31567 -5.625 0 16.25 29.45)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="b39m61b9a"/><stop offset="1" class="l5oafwb0y"/></radialGradient><radialGradient id="iwGUgtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .68286 -1.13306 0 11.04 29.45)" gradientUnits="userSpaceOnUse"><stop class="xm_jq3gjp"/><stop offset="1" class="xqkt32x4y"/></radialGradient><radialGradient id="iXvDIOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .5813 -1.1875 0 21.188 29.45)" gradientUnits="userSpaceOnUse"><stop class="q7lrj0b3i"/><stop offset="1" class="xqkt32x4y"/></radialGradient><radialGradient id="i9kko1c" cx="0" cy="0" r="1" gradientTransform="matrix(.00781 .32813 -3.28124 .07812 18.523 29.219)" gradientUnits="userSpaceOnUse"><stop class="soy92ebql"/><stop offset="1" class="ov_z5ubba"/></radialGradient><radialGradient id="iCfngnd" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 .375 -3.66323 .15264 13.594 29.719)" gradientUnits="userSpaceOnUse"><stop class="soy92ebql"/><stop offset="1" class="ov_z5ubba"/></radialGradient><radialGradient id="iUkIIed" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49316 -5.21875 0 16.422 21.46)" gradientUnits="userSpaceOnUse"><stop class="aur-70boy"/><stop offset="1" class="daflqccwr"/></radialGradient><radialGradient id="iqiCy3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.625 -9.55005 0 21.325 11.436)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="gbsbo7yev"/><stop offset=".556" class="o-su4032j"/><stop offset="1" class="beh5jbykv"/></radialGradient><radialGradient id="iHp8fwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -6.3667 0 6.813 11.688)" gradientUnits="userSpaceOnUse"><stop class="gbsbo7yev"/><stop offset="1" class="ezaf-6_oj"/></radialGradient><radialGradient id="ifVzuce" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 3.3125 -4.08922 1.08019 14.875 16.125)" gradientUnits="userSpaceOnUse"><stop class="x5pnnactl"/><stop offset="1" class="pr2wzbb_i"/></radialGradient><radialGradient id="iXwOqde" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -5.70172 0 7.514 16.188)" gradientUnits="userSpaceOnUse"><stop class="xa7-mibcc"/><stop offset="1" class="zb-gkmb9d"/></radialGradient><linearGradient id="irAlbbe" x1="6" x2="26.159" y1="11.688" y2="11.688" gradientUnits="userSpaceOnUse"><stop class="pbuigqb6f"/><stop offset=".474" class="z0lwrcbvq"/><stop offset=".682" class="ozpkcpkqy"/></linearGradient><linearGradient id="iGz8xxw" x1="16.079" x2="16.079" y1="2" y2="2.688" gradientUnits="userSpaceOnUse"><stop class="schd3yppj"/><stop offset="1" class="gf4uxwb2n"/></linearGradient><linearGradient id="iKLbJAe" x1="15.938" x2="16.075" y1="28.891" y2="31.266" gradientUnits="userSpaceOnUse"><stop class="pbuigqb6f"/><stop offset=".481" class="ozpkcpkqy"/></linearGradient><linearGradient id="i64TQvc" x1="15.25" x2="16.969" y1="25.563" y2="25.563" gradientUnits="userSpaceOnUse"><stop class="jsb3l684h"/><stop offset=".318" class="czvwxu8kf"/><stop offset=".736" class="u4iiu08tn"/><stop offset="1" class="ob8vtubab"/></linearGradient><linearGradient id="iIRgz8d" x1="16.5" x2="16.5" y1="20.563" y2="15.106" gradientUnits="userSpaceOnUse"><stop offset=".092" class="uf-tq3bzl"/><stop offset=".367" class="lhej4zr-u"/><stop offset=".664" class="zbps2veuf"/><stop offset="1" class="edo79ob9p"/></linearGradient><linearGradient id="iRWZhmb" x1="16.082" x2="16.082" y1="10.06" y2="10.625" gradientUnits="userSpaceOnUse"><stop class="x0fw4fb6z"/><stop offset="1" class="z-qb1ab6b"/></linearGradient><linearGradient id="iLAFqob" x1="18.925" x2="22.813" y1="4.123" y2="13.375" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".983" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wine-glass" /></template>
<style>
.aur-70boy {
  stop-color: var(--svg-color--bde9ff, #BDE9FF);
}

.b39m61b9a {
  stop-color: var(--svg-color--bedbf3, #BEDBF3);
  stop-opacity: 0;
}

.beh5jbykv {
  stop-color: var(--svg-color--e6229d, #E6229D);
  stop-opacity: 0;
}

.ct58cdbwd {
  stop-color: var(--svg-color--c0d7f0, #C0D7F0);
}

.czvwxu8kf {
  stop-color: var(--svg-color--c7f1ff, #C7F1FF);
}

.daflqccwr {
  stop-color: var(--svg-color--bde9ff, #BDE9FF);
  stop-opacity: 0;
}

.dj7v9n8vp {
  fill: var(--svg-color--e21b95, #E21B95);
  d: path("M23.21 10.06H8.95c-.43 0-.83.26-1 .66a5.39 5.39 0 0 0 2.54 6.94l4.46 2.23c.71.35 1.54.35 2.25 0l4.47-2.23c2.55-1.28 3.67-4.32 2.54-6.94c-.17-.41-.56-.66-1-.66");
}

.edo79ob9p {
  stop-color: var(--svg-color--c940b0, #C940B0);
  stop-opacity: 0;
}

.ezaf-6_oj {
  stop-color: var(--svg-color--ff73cc, #FF73CC);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gbsbo7yev {
  stop-color: var(--svg-color--ff73cb, #FF73CB);
}

.gcr3ehbfv {
  d: path("M23.21 10.06H8.95c-.43 0-.83.26-1 .66a5.39 5.39 0 0 0 2.54 6.94l4.46 2.23c.71.35 1.54.35 2.25 0l4.47-2.23c2.55-1.28 3.67-4.32 2.54-6.94c-.17-.41-.56-.66-1-.66");
}

.gf4uxwb2n {
  stop-color: var(--svg-color--badef8, #BADEF8);
  stop-opacity: 0;
}

.jgs9rpm3b {
  d: path("m25.6 10.12l-3.29-7.66a.75.75 0 0 0-.69-.46H10.54c-.3 0-.58.18-.69.46l-3.29 7.66A6.89 6.89 0 0 0 9.81 19l4.92 2.46c.34.17.56.52.56.9v6.36H11.8c-.4 0-.75.31-.76.72s.32.74.73.74h8.58c.4 0 .75-.31.76-.72a.724.724 0 0 0-.73-.74h-3.55v-6.35c0-.38.22-.73.56-.9l4.95-2.48a6.873 6.873 0 0 0 3.26-8.87");
}

.jsb3l684h {
  stop-color: var(--svg-color--bbdbf5, #BBDBF5);
}

.l5oafwb0y {
  stop-color: var(--svg-color--bbdaf5, #BBDAF5);
}

.lhej4zr-u {
  stop-color: var(--svg-color--a969bd, #A969BD);
}

.o-su4032j {
  stop-color: var(--svg-color--ff38b5, #FF38B5);
}

.ob8vtubab {
  stop-color: var(--svg-color--c2e6fe, #C2E6FE);
}

.ov_z5ubba {
  stop-color: var(--svg-color--d4fcff, #D4FCFF);
  stop-opacity: 0;
}

.ozpkcpkqy {
  stop-color: var(--svg-color--d3f6ff, #D3F6FF);
}

.pbuigqb6f {
  stop-color: var(--svg-color--c7e7ff, #C7E7FF);
}

.pr2wzbb_i {
  stop-color: var(--svg-color--c348b4, #C348B4);
  stop-opacity: 0;
}

.q7lrj0b3i {
  stop-color: var(--svg-color--c3e2fb, #C3E2FB);
}

.qk2s94bex {
  d: path("M11.8 28.72c-.4 0-.75.31-.76.72s.32.74.73.74h8.58c.4 0 .75-.31.76-.72a.724.724 0 0 0-.73-.74z");
}

.schd3yppj {
  stop-color: var(--svg-color--badef8, #BADEF8);
}

.smdbqjopz {
  d: path("M14.73 21.46c.34.17.56.52.56.9v6.36h1.54v-6.35c0-.38.22-.73.56-.9z");
}

.soy92ebql {
  stop-color: var(--svg-color--d3fbff, #D3FBFF);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tvicpkgom {
  stop-color: var(--svg-color--bfd7ef, #BFD7EF);
  stop-opacity: 0;
}

.u4iiu08tn {
  stop-color: var(--svg-color--cff8ff, #CFF8FF);
}

.uf-tq3bzl {
  stop-color: var(--svg-color--9162ac, #9162AC);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wl4ju0bqw {
  d: path("M22.37 12.93c-.39 0-.76-.23-.92-.61l-3.29-7.66c-.22-.51.02-1.1.52-1.31a1 1 0 0 1 1.31.52l3.29 7.66c.22.51-.02 1.1-.52 1.31q-.195.09-.39.09");
}

.x0fw4fb6z {
  stop-color: var(--svg-color--da318b, #DA318B);
}

.x5pnnactl {
  stop-color: var(--svg-color--c24ab6, #C24AB6);
}

.xa7-mibcc {
  stop-color: var(--svg-color--b23e95, #B23E95);
}

.xm_jq3gjp {
  stop-color: var(--svg-color--bddaf3, #BDDAF3);
}

.xqkt32x4y {
  stop-color: var(--svg-color--badaf5, #BADAF5);
  stop-opacity: 0;
}

.z-qb1ab6b {
  stop-color: var(--svg-color--da318b, #DA318B);
  stop-opacity: 0;
}

.z0lwrcbvq {
  stop-color: var(--svg-color--c2e9ff, #C2E9FF);
}

.zb-gkmb9d {
  stop-color: var(--svg-color--b33c93, #B33C93);
  stop-opacity: 0;
}

.zbps2veuf {
  stop-color: var(--svg-color--cc4ab7, #CC4AB7);
}

</style>
