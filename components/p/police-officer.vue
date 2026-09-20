<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="svh_srr7u"/><radialGradient id="SVGxyhdLbWv" cx="99.568" cy="47.313" r="24.68" gradientTransform="matrix(1 0 0 .4912 -20.914 57.446)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGxyhdLbWv)" class="hetbgtn3f"/><radialGradient id="SVGksn1sc8m" cx="76.66" cy="50.992" r="7.158" gradientTransform="rotate(154.924 84.754 60.186)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGksn1sc8m)" class="ajknltbkq"/><radialGradient id="SVGsGdgwdYz" cx="95.367" cy="71.203" r="31.197" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 30.795 156.327)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGsGdgwdYz)" class="ftkslacdg"/><radialGradient id="SVGUI2CgOAH" cx="45.167" cy="71.203" r="31.197" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 100.972 106.267)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGUI2CgOAH)" class="s_aipiomt"/><radialGradient id="SVGaeixJbWG" cx="49.369" cy="47.313" r="24.68" gradientTransform="matrix(-1 0 0 .4912 98.738 57.446)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGaeixJbWG)" class="uo9y6mb6d"/><radialGradient id="SVGWWaLMgxl" cx="26.461" cy="50.992" r="7.158" gradientTransform="rotate(205.076 4.357 51.532)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGWWaLMgxl)" class="d_5x5rbqd"/><linearGradient id="SVGn7qGEdzl" x1="64" x2="64" y1="31.528" y2="2.285" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="ipx867izl"/><stop offset=".223" class="ct1v36l1g"/><stop offset=".629" class="vv57tob_q"/><stop offset="1" class="pr3reub9e"/></linearGradient><path fill="url(#SVGn7qGEdzl)" class="hmqldjlhw"/><path class="a6d4t0urf"/><path class="iyxgvsb0t"/><linearGradient id="SVGh2UxF26a" x1="116.379" x2="106.54" y1="9.418" y2="9.418" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="g-snsxksh"/><stop offset=".099" class="vnlt8_bly"/><stop offset=".68" class="s50tmz3go"/><stop offset="1" class="a6x862b5i"/></linearGradient><path fill="url(#SVGh2UxF26a)" class="lgaeoxboy"/><linearGradient id="SVGze2X8cwl" x1="11.575" x2="21.414" y1="9.418" y2="9.418" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="g-snsxksh"/><stop offset=".099" class="vnlt8_bly"/><stop offset=".68" class="s50tmz3go"/><stop offset="1" class="a6x862b5i"/></linearGradient><path fill="url(#SVGze2X8cwl)" class="sp8_w6bvq"/><g class="sou-2h8ck"><path class="i0wjl-kcd"/><path class="n-jv4lbdp"/><path class="bonve4tpf"/></g><path class="c6cjtiuui"/><path class="c44_wk_pk"/><path class="q0l68pbsr"/><path class="u7bcg7bpj"/><path class="ci4u0ob-d"/><path class="viqr_rxdd"/><path class="i_kemh51j"/><g class="y73_33btq"><ellipse class="xm_cxnkcf"/><ellipse class="qi4mcqr9e"/></g><path class="r26kp3x7g"/><path class="ca6fyc6yp"/><radialGradient id="SVGpUaBGbrt" cx="80.442" cy="87.144" r="34.378" gradientTransform="matrix(.3076 .9515 .706 -.2282 -5.827 -15.8)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGpUaBGbrt)" class="h1ygylb6u"/><radialGradient id="SVGqb0pvdKG" cx="157.584" cy="62.016" r="26.344" gradientTransform="matrix(-.9378 -.3944 -.2182 .5285 229.242 48.969)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGqb0pvdKG)" class="q8a3m1brl"/><radialGradient id="SVGlhZ1dbIQ" cx="44.226" cy="102.075" r="15.13" gradientTransform="matrix(-.9657 -.2598 -.2432 .9037 111.758 -54.83)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGlhZ1dbIQ)" class="xj69ugbuu"/><radialGradient id="SVGGaGOpu4Q" cx="40.498" cy="87.078" r="16.513" gradientTransform="rotate(187.833 -2.787 78.87)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGGaGOpu4Q)" class="xgdciwbsi"/><linearGradient id="SVGgvJ5vd9I" x1="64.056" x2="64.056" y1="103.667" y2="82.887" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="g-snsxksh"/><stop offset=".099" class="vnlt8_bly"/><stop offset=".68" class="s50tmz3go"/><stop offset="1" class="a6x862b5i"/></linearGradient><path fill="url(#SVGgvJ5vd9I)" class="elqf0kbnq"/><linearGradient id="SVG3q3flcOR" x1="64" x2="64" y1="123.648" y2="93.687" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="ipx867izl"/><stop offset=".011" class="p3o4jriyj"/><stop offset=".298" class="pr42jabxt"/><stop offset=".568" class="jlxsv36ro"/><stop offset=".809" class="k09q0hbdc"/><stop offset="1" class="pr3reub9e"/></linearGradient><path fill="url(#SVG3q3flcOR)" class="dxufsac0r"/><path class="ytuhcnavm"/><path class="lz4slvzox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:police-officer" /></template>
<style>
.a6d4t0urf {
  fill: var(--svg-color--283593, #283593);
  d: path("M76.32 106.27s6.88.59 13.84 2.73c13 4 16.91-2.86 16.91-2.86s-14.22-9.32-32.22-9.45c0 0-1.19 8.85 1.47 9.58M20.59 106s4 7 17 3c6.96-2.14 13.84-2.73 13.84-2.73c2.66-.73 1.47-9.58 1.47-9.58c-18 .12-32.31 9.31-32.31 9.31");
}

.a6x862b5i {
  stop-color: var(--svg-color--333, #333);
}

.ajknltbkq {
  d: path("M95.07 81.82c-4.51-7 4.78-9.59 4.78-9.59l.01.01c-1.54 2.18-2.2 4.1-1.16 6c1.31 2.39 4.92 2.74 4.92 2.74s-4.68 4.75-8.55.84");
}

.bonve4tpf {
  d: path("m16.65 115.71l-3.88-.16c-.28.01-.51.2-.52.48s.2.51.48.52l3.38.14l.91 1.31l-3.94 6h1.2l3.95-6.01z");
}

.c44_wk_pk {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M54.92 86.08v13.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17V86.08z");
}

.c6cjtiuui {
  fill: var(--svg-color--212121, #212121);
  d: path("m63.99 121.94l9.32-17.08h-19.9z");
}

.ca6fyc6yp {
  fill: var(--svg-color--543930, #543930);
  d: path("M101.15 23.27c-2.42-3.44-7.65-8-12.16-8.3c-.86-4.3-5.56-7.89-10.03-9.28c-11.99-3.72-19.78.45-24 2.72c-.88.47-6.59 3.58-10.5 1.35c-2.44-1.39-10.1-2.24-7.76 5.97c-2.69.11-6.27 1.25-8.32 5.05c-2.47 4.58-1.86 8.45-1.3 10.32c-2.47 2.05-5.69 6.45-3.94 12.23c1.33 4.41 7.5 6.46 7.5 6.46c-.79 8.12-.63 13.2.06 15.27c.12.36.61.33.71-.05c1.13-4.11 5.96-18.13 5.73-20.52c0 0 10.86-2.22 21.2-9.98c2.08-1.56 4.32-2.88 6.7-3.85c12.63-5.13 15.47 3.66 15.47 3.66s8.8-1.74 11.94 11.02c1.2 4.89 3.39 12.85 4.2 18.52c.06.4.57.49.71.12c.84-2.26 1.31-6.7 1.56-11.19c.08-1.56 4-3.62 5.38-10.24c1.81-8.64-1.38-16.77-3.15-19.28");
}

.ci4u0ob-d {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M64 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S97.52 83.1 97.52 56.46c0-26.78-16.12-45.39-33.52-45.39");
}

.ct1v36l1g {
  stop-color: var(--svg-color--386eda, #386eda);
}

.d_5x5rbqd {
  d: path("M32.95 81.82c4.51-7-4.78-9.59-4.78-9.59l-.01.01c1.54 2.18 2.2 4.1 1.16 6c-1.31 2.39-4.92 2.74-4.92 2.74s4.69 4.75 8.55.84");
}

.dxufsac0r {
  d: path("M19.96 34.5c1.71 6.19 3.35 8.81 3.35 8.81C25.04 41.31 35.35 32 63.93 32h.16c28.58 0 38.42 9.36 40.16 11.36c0 0 2.07-2.8 3.78-8.99C112 20.05 92.35 4 64.06 4c-28.23 0-48.05 16.2-44.1 30.5");
}

.elqf0kbnq {
  d: path("M63.79 24.22c-33.6 0-38.98 11.36-38.98 11.36s10.36 9.91 38.98 10.1c28.63-.19 39.51-10.73 39.51-10.73s-5.91-10.73-39.51-10.73");
}

.ftkslacdg {
  d: path("M104.6 43.98c4.64 10.37.9 21.33-2.97 26.05c-.54.65-2.83 3.19-3.29 5.23c0 0-9.89-13.98-12.89-21.98c-.6-1.6-1.14-3.23-1.25-4.91c-.08-1.26.07-2.74.73-3.8c.81-1.3 19.14-1.68 19.14-1.68c-.01.01.53 1.09.53 1.09");
}

.g-snsxksh {
  stop-color: var(--svg-color--666, #666);
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.h1ygylb6u {
  d: path("M98.9 52.83c.08-1.56 4-3.62 5.38-10.24c.14-.7.26-1.4.37-2.12c.95-7.84-1.87-14.9-3.49-17.21c-2.24-3.18-6.88-7.32-11.13-8.15c-.37-.05-.73-.09-1.07-.11c0 0 .37 1.97-.38 3.55c-.97 2.06-3.07 2.55-3.07 2.55C97.07 32.42 96.68 42.15 98.9 52.83");
}

.hetbgtn3f {
  d: path("M63.99 95.79V85.3l28.59-2.47l2.74 3.5s-5.89 9.47-22.23 9.47z");
}

.hmqldjlhw {
  d: path("M64.14 96H64c-25.65.03-52 7.1-52 24.99V124h104v-3.01C116 104.12 89.9 96 64.14 96");
}

.i_kemh51j {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M67.86 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.3-.71-.05-1.37-.69-1.63");
}

.i0wjl-kcd {
  d: path("m109.33 113.99l4.56-.08c.41-.01.74-.35.74-.76s-.32-.71-.76-.74l-5.44.09l-3.02 5.55l4.23 5.95h1.84l-4.31-6.05z");
}

.ipx867izl {
  stop-color: var(--svg-color--3b78e7, #3b78e7);
}

.iyxgvsb0t {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M45.75 119.71H34.83c-1.2 0-2.17-.97-2.17-2.17s.97-2.17 2.17-2.17h10.92c1.2 0 2.17.97 2.17 2.17s-.97 2.17-2.17 2.17");
}

.jlxsv36ro {
  stop-color: var(--svg-color--2d46a8, #2d46a8);
}

.k09q0hbdc {
  stop-color: var(--svg-color--293998, #293998);
}

.lgaeoxboy {
  d: path("m113.88 113.17l-5 .08l-2.34 4.29l4.83 6.46h4.99c.26-7.38-2.48-10.83-2.48-10.83");
}

.lz4slvzox {
  fill: var(--svg-color--fc0, #fc0);
  d: path("M71.28 13.2c-.26 0-.5.12-.64.33c-.55.84-1.36 1.4-2.79 1.4c-1.39 0-2.4-1.28-3.01-2.07c-.19-.25-.49-.41-.82-.41s-.63.16-.82.41c-.6.79-1.56 2.07-2.95 2.07c-1.43 0-2.24-.57-2.79-1.4a.76.76 0 0 0-.64-.33c-.24 0-.47.11-.61.29l-.31.4c-.37.48-.43 1.12-.15 1.65c.42.8.64 1.68.64 2.57v3.48c0 2.54 4.14 7.72 7.65 7.72s7.65-5.18 7.65-7.72v-3.48c0-.89.22-1.77.64-2.57c.28-.53.22-1.17-.15-1.65l-.31-.4c-.12-.18-.35-.29-.59-.29");
}

.n-jv4lbdp {
  d: path("m111.84 116.69l3.38-.14c.28-.01.49-.24.48-.52s-.25-.47-.52-.48l-3.87.16l-1.57 2.28l3.95 6.01h1.2l-3.94-5.99zm-92.31-4.18l-5.44-.09h-.01c-.41 0-.74.33-.75.74s.32.76.74.76l4.57.08l2.15 3.96l-4.32 6.04h1.84l4.23-5.95z");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.p3o4jriyj {
  stop-color: var(--svg-color--3b77e6, #3b77e6);
}

.pr3reub9e {
  stop-color: var(--svg-color--283593, #283593);
}

.pr42jabxt {
  stop-color: var(--svg-color--335bc2, #335bc2);
}

.q0l68pbsr {
  fill: var(--svg-color--3674ce, #3674ce);
  d: path("m47.1 97.18l-8 16.22l10.87-3.26l14.02 11.8l-9.11-25.67zm26.02-.91l-9.11 25.67l14.8-11.64l10.09 3.1l-8-16.22z");
}

.q8a3m1brl {
  d: path("M77.72 5.33c6.67 1.77 10.02 5.12 11.26 9.65c.37 1.34 1.19 14.06-23.14-.36c-8.81-5.23-6.39-8.46-5.36-8.83c4-1.43 9.8-2.43 17.24-.46");
}

.qi4mcqr9e {
  cx: 80.44px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.r26kp3x7g {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M54.8 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55m32.87 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55");
}

.s_aipiomt {
  d: path("M23.42 43.98c-4.64 10.37-.9 21.33 2.98 26.05c.54.65 2.83 3.19 3.29 5.23c0 0 9.89-13.98 12.89-21.98c.6-1.6 1.14-3.23 1.25-4.91c.08-1.26-.07-2.74-.73-3.8c-.81-1.3-1.81-.95-3.25-.95c-2.74 0-14.71-.73-15.64-.73c0 .01-.79 1.09-.79 1.09");
}

.s50tmz3go {
  stop-color: var(--svg-color--3f3f3f, #3f3f3f);
}

.sou-2h8ck {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
}

.sp8_w6bvq {
  d: path("m19.08 113.25l-5-.08s-2.74 3.46-2.48 10.83h4.99l4.83-6.46z");
}

.svh_srr7u {
  fill: var(--svg-color--543930, #543930);
  d: path("M98.72 78.24c-1.34-2.44.13-4.91 2.67-7.94c4-4.77 7.96-15.61 3.19-26.32c.02-.06-.91-1.83-.89-1.89l-1.71-.09c-.55-.08-19.26-.12-37.98-.12s-37.43.04-37.98.12c0 0-2.62 1.92-2.6 1.98c-4.77 10.71-.8 21.55 3.19 26.32c2.54 3.03 4.01 5.5 2.67 7.94c-1.31 2.39-4.92 2.74-4.92 2.74s.71 2.46 2.66 3.79c1.81 1.23 4.08 1.53 5.66 1.57c0 0 5.89 9.47 22.23 9.47H73.1c16.34 0 22.23-9.47 22.23-9.47c1.58-.04 3.85-.33 5.66-1.57c1.94-1.33 2.66-3.79 2.66-3.79s-3.62-.36-4.93-2.74");
}

.u7bcg7bpj {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M91.33 50.43H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.81-11.41-10.7-11.41");
}

.uo9y6mb6d {
  d: path("M64.03 95.79V85.3l-28.59-2.47l-2.74 3.5s5.89 9.47 22.23 9.47z");
}

.viqr_rxdd {
  fill: var(--svg-color--795548, #795548);
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.vnlt8_bly {
  stop-color: var(--svg-color--606060, #606060);
}

.vv57tob_q {
  stop-color: var(--svg-color--3052b8, #3052b8);
}

.xgdciwbsi {
  d: path("M26.87 31.28c-2.33 2.02-5.58 6.55-3.65 12.25c1.47 4.35 7.44 6.26 7.44 6.26c0 .02 1.2.4 1.82.4l2.25-21.38c-2.83 0-5.58.86-7.4 2.11c0 .03-.47.33-.46.36");
}

.xj69ugbuu {
  d: path("m41.1 16.43l-4.39-.71c-.17 0-.76.05-1.08.1c-2.5.35-5.49 1.63-7.24 4.95c-1.9 3.6-2 6.73-1.64 8.82c.1.71.34 1.5.34 1.5s2.33-2.15 7.63-2.29z");
}

.xm_cxnkcf {
  cx: 47.56px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.y73_33btq {
  fill: var(--svg-color--404040, #404040);
}

.ytuhcnavm {
  fill: var(--svg-color--3b78e7, #3b78e7);
  d: path("M100.04 35.61a4.6 4.6 0 0 0-1.74-2.81c-3.78-2.9-15.09-10.1-34.24-10.1c-19.65 0-30.65 7.19-34.3 10.1c-.87.69-1.46 1.67-1.67 2.75l-.01.06c-.25 1.32.09 2.56.79 3.54C34.7 35.86 45.53 32 63.93 32h.16c18.7 0 29.38 4.01 35.01 7.34c.81-.99 1.21-2.32.94-3.73");
}

</style>
