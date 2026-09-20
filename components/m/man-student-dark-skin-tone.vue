<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kedit2b-e"/><path class="spx-o2bmf"/><g class="d2ol71wkq"><ellipse class="kh5vn5bjb"/><ellipse class="ofdvg0zwa"/></g><path class="wju5g7buz"/><path class="zt98l_buo"/><path class="a5yf-5b_g"/><radialGradient id="SVGhNVknbSf" cx="63.996" cy="46.779" r="37.877" gradientTransform="matrix(1 0 0 1.1282 0 -6.112)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGhNVknbSf)" class="rbpyg7bud"/><path class="v6_mes92y"/><path class="oavj2ob8u"/><path class="w8z81905y"/><ellipse class="gnzz9u18n"/><path class="as2ihek-m"/><linearGradient id="SVG5eYfhejp" x1="64.01" x2="64.01" y1=".649" y2="29.29" gradientUnits="userSpaceOnUse"><stop offset=".003" class="a72as_i6q"/><stop offset=".472" class="d_wzpg_av"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVG5eYfhejp)" class="cxo62_vmv"/><linearGradient id="SVGjn2PwcCz" x1="64" x2="64" y1=".816" y2="31.816" gradientUnits="userSpaceOnUse"><stop offset=".003" class="aplh-7tkj"/><stop offset=".324" class="a0m3qtb0g"/><stop offset=".955" class="osi2yu8vz"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGjn2PwcCz)" class="ai20ioboy"/><linearGradient id="SVGMfZLme6Y" x1="13.892" x2="114.721" y1="18.98" y2="18.98" gradientUnits="userSpaceOnUse"><stop offset=".001" class="fy7ry9ban"/><stop offset=".3" class="gjuor2bpt"/><stop offset=".7" class="gjuor2bpt"/><stop offset="1" class="fy7ry9ban"/></linearGradient><path fill="url(#SVGMfZLme6Y)" class="c7mmmac7w"/><path class="xdm-vz3fo"/><radialGradient id="SVGxTdVmatN" cx="63.995" cy="122.603" r="54.172" gradientTransform="matrix(1 0 0 .5247 0 58.274)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="wk_lp_wlk"/><stop offset="1" class="aplh-7tkj"/></radialGradient><path fill="url(#SVGxTdVmatN)" class="ba5mhrsid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-student-dark-skin-tone" /></template>
<style>
.a0m3qtb0g {
  stop-color: var(--svg-color--505050, #505050);
}

.a5yf-5b_g {
  fill: var(--svg-color--232020, #232020);
  d: path("M64.02 5.03h-.04c-45.44.24-36.13 50.14-36.13 50.14s2.04 5.35 2.97 7.71c.13.34.63.3.71-.05c.97-4.34 4.46-19.73 6.22-24.41a6.075 6.075 0 0 1 6.79-3.83c4.46.81 11.55 1.81 19.38 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.75 4.66 5.22 19.96 6.2 24.36c.08.36.58.39.71.05l2.98-7.67c.02.01 9.32-49.89-36.11-50.13");
}

.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.ai20ioboy {
  d: path("M64 4.98s-21.17.25-52 8c0 0 35.41 9.67 52 9.38c16.59.29 52-9.38 52-9.38c-30.83-7.75-52-8-52-8");
}

.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.as2ihek-m {
  fill: var(--svg-color--504f4f, #504f4f);
  d: path("M13.123 53.02c-.55 0-1-.45-1-1v-38c0-.55.45-1 1-1s1 .45 1 1v38c0 .56-.45 1-1 1");
}

.ba5mhrsid {
  d: path("M114.5 120.99c0-14.61-21.75-21.54-40.72-23.1l-8.6 11.03c-.28.36-.72.58-1.18.58s-.9-.21-1.18-.58L54.2 97.87c-10.55.81-40.71 4.75-40.71 23.12V124h101z");
}

.c7mmmac7w {
  d: path("M116 12.98c-30.83-7.75-52-8-52-8s-21.17.25-52 8v.77c0 1.33.87 2.5 2.14 2.87c3.72 1.1 13.13 3.69 18.18 4.71c0 0-.96 1.56-1.83 3.53c0 0 8.14 5.55 33.52 8.12c25.38-2.56 33.76-7.58 33.76-7.58c-.88-1.81-1.79-3.49-1.79-3.49c4.5-.74 14.23-4.07 17.95-5.26c1.25-.4 2.09-1.55 2.09-2.86v-.81z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.cxo62_vmv {
  d: path("M116 12.98c-30.83-7.75-52-8-52-8s-21.17.25-52 8v.77c0 1.33.87 2.5 2.14 2.87c3.72 1.1 13.13 3.53 18.18 4.54c-.08.08-1.1 1.87-1.83 3.53c0 0 8.14 5.72 33.52 8.28c25.38-2.56 33.76-7.58 33.76-7.58c-.88-1.81-1.79-3.49-1.79-3.49c4.5-.74 14.23-4.07 17.95-5.26c1.25-.4 2.09-1.55 2.09-2.86v-.8z");
}

.d_wzpg_av {
  stop-color: var(--svg-color--353535, #353535);
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.fy7ry9ban {
  stop-color: var(--svg-color--bfbebe, #bfbebe);
}

.g00j4bcaa {
  stop-color: var(--svg-color--444140, #444140);
}

.gjuor2bpt {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0;
}

.gnzz9u18n {
  cx: 13.123px;
  cy: 53.05px;
  fill: var(--svg-color--ffca28, #ffca28);
  rx: 2.76px;
  ry: 2.63px;
}

.kedit2b-e {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M73.76 89.08H54.23v19.33c0 4.85 3.98 8.78 8.88 8.78h1.77c4.9 0 8.88-3.93 8.88-8.78zm17.57-38.67H36.67c-5.89 0-10.71 5.14-10.71 11.41c0 6.28 4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41c.01-6.27-4.81-11.41-10.7-11.41");
}

.kh5vn5bjb {
  cx: 47.56px;
  cy: 58.79px;
  rx: 4.93px;
  ry: 5.1px;
}

.oavj2ob8u {
  fill: var(--svg-color--e8ad00, #e8ad00);
  d: path("M15.373 54.28c-1.24 0-2.25.96-2.25 2.14v9.2c0 1.18 1.01 2.14 2.25 2.14s2.25-.96 2.25-2.14v-9.2c0-1.18-1.01-2.14-2.25-2.14m-4.5 0c-1.24 0-2.25.96-2.25 2.14v9.2c0 1.18 1.01 2.14 2.25 2.14s2.25-.96 2.25-2.14v-9.2c0-1.18-1.01-2.14-2.25-2.14");
}

.ofdvg0zwa {
  cx: 80.44px;
  cy: 58.79px;
  rx: 4.93px;
  ry: 5.1px;
}

.osi2yu8vz {
  stop-color: var(--svg-color--242424, #242424);
}

.qpo2vg_rh {
  stop-color: var(--svg-color--444140, #444140);
  stop-opacity: 0;
}

.rbpyg7bud {
  d: path("M100.15 55.17s9.31-49.9-36.13-50.14h-.04c-.71 0-1.4.02-2.08.05c-1.35.06-2.66.16-3.92.31h-.04c-.09.01-.17.03-.26.04c-38.25 4.81-29.84 49.74-29.84 49.74l2.98 7.68c.13.34.62.31.7-.05c.98-4.39 4.46-19.71 6.22-24.37a6.08 6.08 0 0 1 6.8-3.83c4.46.8 11.55 1.8 19.38 1.8h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.76 4.68 5.25 20.1 6.21 24.42c.08.36.57.39.7.05c.94-2.35 3-7.72 3-7.72");
}

.spx-o2bmf {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M64 11.05c-17.4 0-33.52 18.61-33.52 45.39c0 26.64 16.61 39.81 33.52 39.81s33.52-13.17 33.52-39.81c0-26.78-16.12-45.39-33.52-45.39");
}

.v6_mes92y {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M40.01 50.72c2.99-4.23 9.78-4.63 13.67-1.48c.62.5 1.44 1.2 1.68 1.98c.4 1.27-.82 2.26-2.01 1.96c-.76-.19-1.47-.6-2.22-.83c-1.37-.43-2.36-.55-3.59-.55c-1.82-.01-2.99.22-4.72.92c-.71.29-1.29.75-2.1.41c-.93-.39-1.27-1.57-.71-2.41m46.06 2.4c-.29-.13-.57-.29-.86-.41c-1.78-.74-2.79-.93-4.72-.92c-1.7.01-2.71.24-4.04.69c-.81.28-1.84.98-2.74.71c-1.32-.4-1.28-1.84-.56-2.76c.86-1.08 2.04-1.9 3.29-2.44c2.9-1.26 6.44-1.08 9.17.55c.89.53 1.86 1.26 2.4 2.18c.78 1.31-.4 3.03-1.94 2.4");
}

.w8z81905y {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M13.123 54.28c-1.24 0-2.25.96-2.25 2.14v11.19c0 1.18 1.01 2.14 2.25 2.14s2.25-.96 2.25-2.14V56.42c0-1.18-1.01-2.14-2.25-2.14");
}

.wju5g7buz {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M67.86 68.04c-.11-.04-.21-.07-.32-.08h-7.07c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.29-.71-.06-1.37-.7-1.63");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.xdm-vz3fo {
  fill: var(--svg-color--212121, #212121);
  d: path("M114.5 120.99c0-14.61-21.75-21.54-40.72-23.1l-8.6 11.03c-.28.36-.72.58-1.18.58s-.9-.21-1.18-.58L54.2 97.87c-10.55.81-40.71 4.75-40.71 23.12V124h101z");
}

.zt98l_buo {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M72.42 76.12c-3.19 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.45 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

</style>
