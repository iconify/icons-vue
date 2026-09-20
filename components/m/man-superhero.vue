<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGQL8n4c7h" x1="79.567" x2="51.086" y1="78.962" y2="40.814" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="ezcsz113k"/></linearGradient><path fill="url(#SVGQL8n4c7h)" class="fr1th1bnm"/><radialGradient id="SVGVA5KL9hS" cx="74.878" cy="64.629" r="18.579" gradientTransform="rotate(200.578 -5.617 80.714)scale(-1 1.9378)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".999" class="gjuor2bpt"/></radialGradient><path fill="url(#SVGVA5KL9hS)" class="c3o6p_bbl"/><linearGradient id="SVG938Hod5x" x1="44.406" x2="59.099" y1="72.898" y2="47.53" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".999" class="gjuor2bpt"/></linearGradient><path fill="url(#SVG938Hod5x)" class="pplze2bny"/><linearGradient id="SVGpMo8J76x" x1="76.007" x2="75.835" y1="86.58" y2="66.902" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rj04jfnia"/><stop offset="1" class="r5vbxk1ae"/></linearGradient><path fill="url(#SVGpMo8J76x)" class="c9f8lgbak"/><path class="qv4ka_bia"/><linearGradient id="SVGlwb2gdTv" x1="50.366" x2="43.808" y1="75.374" y2="89.607" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="wi8v79m_m"/></linearGradient><path fill="url(#SVGlwb2gdTv)" class="h_dav37mp"/><path class="a-v9uefku"/><linearGradient id="SVGEb8ZfbUI" x1="55.129" x2="50.129" y1="43.972" y2="36.222" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="l163gnb3q"/><stop offset=".841" class="cqr7j4bgr"/></linearGradient><path fill="url(#SVGEb8ZfbUI)" class="z-k93uvrs"/><linearGradient id="SVGHtA1BbSN" x1="69.79" x2="60.641" y1="55.927" y2="35.386" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rj04jfnia"/><stop offset="1" class="r5vbxk1ae"/></linearGradient><path fill="url(#SVGHtA1BbSN)" class="d3k9k1bej"/><path class="av9i0v24v"/><linearGradient id="SVGUsxvhblt" x1="62.701" x2="84.321" y1="65.551" y2="60.826" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="yac5kp3-q"/><stop offset=".23" class="ai1a8abib"/><stop offset=".742" class="ai1a8abib"/><stop offset="1" class="yac5kp3-q"/></linearGradient><path fill="url(#SVGUsxvhblt)" class="led8d0bhz"/><path class="itxgn3vuq"/><path class="hy1ry5b_q"/><path class="d925exa8n"/><linearGradient id="SVG6DoXccGG" x1="77.247" x2="77.247" y1="83.257" y2="73.402" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="dl-6blb5x"/><stop offset="1" class="g3c_jbvil"/></linearGradient><path fill="url(#SVG6DoXccGG)" class="yor6rcbnf"/><linearGradient id="SVGWzkfQbdy" x1="66.098" x2="43.784" y1="27.623" y2="5.309" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="ezcsz113k"/></linearGradient><path fill="url(#SVGWzkfQbdy)" class="f936r0mwr"/><path class="crlr_4g4j"/><path class="w3ewgyb1k"/><path class="jqb568bki"/><linearGradient id="SVGiJkax1SQ" x1="98.368" x2="84.559" y1="104.084" y2="124.97" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="wi8v79m_m"/></linearGradient><path fill="url(#SVGiJkax1SQ)" class="tx-hj233l"/><path class="x11b2bb6t"/><path class="f6jgu4rnd"/><path class="nwrko_bjy"/><g class="y73_33btq"><ellipse transform="rotate(-1.175 70.38 24.41)" class="hxv607bng"/><ellipse transform="rotate(-1.175 79.616 24.221)" class="hbf-27bmo"/></g><path class="pu-7lsbti"/><path class="ix3of2b4c"/><path class="gymjon6jd"/><path class="y3jqodvht"/><radialGradient id="SVGOzmqYbZV" cx="74.921" cy="106.818" r="10.721" gradientTransform="matrix(.9997 -.026 -.0293 -1.1278 3.027 143.342)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGOzmqYbZV)" class="ya4pnpsxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-superhero" /></template>
<style>
.a-v9uefku {
  fill: none;
  d: path("M41.61 38.62c.59-1.08 2.44-1.82 3.77-2.23c.81-.25 1.67.17 1.99.94l1.97 4.72c.24.58.13 1.25-.29 1.73l-1.85 2.08c.68.92 1.53 1.66 2.51 2.25c1.67 1.01 3.34.97 3.51 1.11c2.12 1.71 3.7 3.71 2.46 6.99c-1.23 3.26-5.47 2.26-5.47 2.26s-4.35-3.06-7.15-9.7c-.91-2.13-2.68-7.91-1.45-10.15");
  opacity: var(--svg-opacity--0-29, 0.29);
}

.ai1a8abib {
  stop-color: var(--svg-color--f44336, #f44336);
}

.av9i0v24v {
  fill: var(--svg-color--212121, #212121);
  d: path("m61.24 63.89l2-3.26c.28-.63 1-.89 1.58-.56c6.62 3.78 10.14 4.79 17.67 4.34c.69-.04 1.26.58 1.21 1.33l-.26 3.51s-2.76 1.56-11.19-.23c-5.98-1.27-11.01-5.13-11.01-5.13");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.c3o6p_bbl {
  d: path("M90.44 73.69c5.41-16.75 1.49-30.51 1.49-30.51s-15.88 5.61-15.92 6.26c-.03.65-10.32 25.11-10.32 25.11S58.2 94.81 48.7 104.23c6.81-.74 12.32-5.31 14.58-5.83c7.09-1.65 12.06-.59 15.33.96c1.79-2.85 8.03-13.89 11.83-25.67");
}

.c9f8lgbak {
  d: path("M103.54 24.36c-1.01-2.75-5.95-10.64-5.95-10.64l-5.74 2.76l2.28 9.86l-10.27 8.55a34.9 34.9 0 0 0-12.95-.52c-2.94-.22-11.3-.12-14.46 7.57l-4.58 10.9l-3.71 1.29c-1.03 2.15 2.35 4.09 4.5 5.11s4 .23 5.76-2.04c1.05-1.36 3.49-5.17 5.27-8c.4 3.03.68 6.73.7 11.23l8.33 4.01l10.14.43c3.7-8.37 5.61-14.74 6.58-19.25c3.35-3.78 12.03-13.6 13.15-15.16c1.38-1.92 1.96-3.35.95-6.1");
}

.cqr7j4bgr {
  stop-color: var(--svg-color--a52714, #a52714);
}

.crlr_4g4j {
  fill: var(--svg-color--ed4132, #ed4132);
  d: path("M53.4 37.12s5.69-7.18 15.85-5.13c7.55 1.52 5.96 6.37 5.96 6.37s-3.81.03-7.24-.76c-3.47-.8-6.56-2.41-8.4-2.22z");
}

.d3k9k1bej {
  d: path("m71.4 66.77l-.25.68c-.45-1.66-1.51-3.18-2.95-3.95c0 0-5.78-1.91-7.23.78c0 0-6.93 10.92-8.03 13.96c-1.11 3.04-1.07 5.52 1.53 7.13c2.1 1.29 4.92.67 7.5-2.26c1.16-1.32 3.84-5.35 5.88-8.48c.32-.5 1.09-.11.88.45l-12.12 31.91l5.41 3.44s16.1-25.73 18.47-30.65s3.21-12.14 3.21-12.14z");
}

.d925exa8n {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("M78.21 44.58c1.89 0 3.28.34 4.25.71l-5.23 5.62l-4.95-5.45c1.27-.4 3.06-.79 5.33-.87c.21-.01.4-.01.6-.01m0-2.07c-.22 0-.44 0-.67.01c-5.77.21-8.73 2.2-8.73 2.2l8.4 9.25l8.48-9.12c-.01 0-2.19-2.34-7.48-2.34");
}

.dl-6blb5x {
  stop-color: var(--svg-color--0d47a1, #0d47a1);
  stop-opacity: 0;
}

.ezcsz113k {
  stop-color: var(--svg-color--ed4132, #ed4132);
}

.f6jgu4rnd {
  fill: var(--svg-color--e59600, #e59600);
  d: path("m74.97 31.28l-3.22.09l.09 2.5c0 3.16 3.36 4.5 3.36 4.5s3.07-1.65 3.07-4.55l-.09-2.62zm7.5-9.75l-2.07.04l-11.21.23l-2.07.04c-1.65.03-2.98 1.5-2.94 3.27s1.42 3.18 3.07 3.14l2.07-.04l11.21-.23l2.07-.04c1.65-.03 2.98-1.5 2.94-3.27c-.03-1.76-1.41-3.17-3.07-3.14");
}

.f936r0mwr {
  d: path("M57.86 97.6s-1.61 9.66-5.58 15.98c-1.94 2.57-5.1 4.68-6.74 9.09c-.75 2.03 3.63 3.96 7.04 2.09c2.05-1.13 5.15-8.03 5.15-8.03c2.74-4.98 10.9-12.92 10.9-12.92c-1.57-7.29-10.77-6.21-10.77-6.21");
}

.fr1th1bnm {
  d: path("M88.03 32.06c.6-.37 1.38-.22 1.78.36c2.1 3.04 7.69 13.17 5.57 32.47C94 77.42 86.9 95.51 84.49 101.37a1.32 1.32 0 0 1-2.12.47c-2.42-2.21-8.33-5.94-19.09-3.44c-3.41.79-14.05 11.45-22.6 1.85c-5.28-5.93-1.43-9.42-1.39-17.95c.05-10.98-11-14.35-14.61-16.15c-.92-.46-.99-1.73-.13-2.29c4.19-2.72 10.07-4 17.46-9.88c9.38-7.45 9.46-14.43 11.38-16.85c.97-1.22 8.61-4.65 8.61-4.65s5.34 1.42 5.6 1.52l9.53 4.21c.38.14.81.1 1.16-.12z");
}

.g19bbhpmg {
  stop-color: var(--svg-color--d23f31, #d23f31);
}

.g3c_jbvil {
  stop-color: var(--svg-color--0d47a1, #0d47a1);
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.gjuor2bpt {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0;
}

.gymjon6jd {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M72.36 21.9c-.29-.43-.95-1.05-2.19-1.02s-1.86.7-2.12 1.15c-.12.2-.08.42.01.56c.08.12.32.24.57.12s.75-.44 1.58-.47c.84-.02 1.35.28 1.61.38s.49-.03.56-.16c.09-.15.11-.37-.02-.56m9.3-.28c-.29-.43-.95-1.05-2.19-1.02c-1.24.04-1.86.7-2.12 1.15c-.12.2-.08.42.01.56c.08.12.32.24.57.12s.75-.44 1.58-.47c.84-.02 1.35.28 1.61.38s.49-.03.56-.16a.54.54 0 0 0-.02-.56");
}

.h_dav37mp {
  d: path("M41.61 38.62c.59-1.08 2.44-1.82 3.77-2.23c.81-.25 1.67.17 1.99.94l1.97 4.72c.24.58.13 1.25-.29 1.73l-1.85 2.08c.68.92 1.53 1.66 2.51 2.25c1.67 1.01 3.34.97 3.51 1.11c2.12 1.71 3.7 3.71 2.46 6.99c-1.23 3.26-5.47 2.26-5.47 2.26s-4.35-3.06-7.15-9.7c-.91-2.13-2.68-7.91-1.45-10.15");
}

.hbf-27bmo {
  cx: 79.61px;
  cy: 24.22px;
  rx: 1.38px;
  ry: 1.43px;
}

.hxv607bng {
  cx: 70.38px;
  cy: 24.41px;
  rx: 1.38px;
  ry: 1.43px;
}

.hy1ry5b_q {
  fill: var(--svg-color--e53935, #e53935);
  d: path("M70.48 45.02c1.28-.56 3.66-1.34 7.09-1.47c.22-.01.43-.01.63-.01c3.09 0 4.98.84 5.95 1.43l-6.94 7.46z");
}

.itxgn3vuq {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("m75.57 66.99l-2.31 1.53c-.46.3-1.07.18-1.37-.28l-1.53-2.31a.985.985 0 0 1 .28-1.37l2.31-1.53a.985.985 0 0 1 1.37.28l1.53 2.31c.3.45.18 1.06-.28 1.37");
}

.ix3of2b4c {
  fill: var(--svg-color--795548, #795548);
  d: path("M77.38 29.42c-.88.56-3.83.64-4.74.13c-.52-.29-1.04.19-.81.65c.22.45 1.86 1.48 3.25 1.44s2.95-1.15 3.14-1.62c.2-.46-.33-.92-.84-.6");
}

.jqb568bki {
  fill: var(--svg-color--212121, #212121);
  d: path("M57.13 40.53s3.26-2.94 8.22-1.75c7.14 1.71 9.86-.41 9.86-.41s5.25 1.89 10.22-.5c3.41-1.64 4.34-7.89 4.34-7.89L88.6 31.3s-4.38 4.77-8.74 6.06c-3.19.95-4.64 1.01-4.64 1.01s-11.76-4.03-14.44-2.91s-3.65 5.07-3.65 5.07");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.l163gnb3q {
  stop-color: var(--svg-color--851f10, #851f10);
}

.led8d0bhz {
  d: path("M83.08 68.94c-8.48.45-13.79-1.08-21.19-5.01c-.58-.31-.81-1.02-.53-1.62l1.19-2.52c.3-.63 1.07-.89 1.69-.56c7.09 3.78 10.86 4.78 18.94 4.34c.74-.04 1.36.59 1.29 1.33l-.23 2.9c-.05.62-.55 1.11-1.16 1.14");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.nwrko_bjy {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M74.53 10.35c-4.89.1-9.31 5.42-9.15 12.94c.15 7.48 4.89 11.09 9.65 10.99c4.75-.1 9.34-3.89 9.19-11.38c-.16-7.52-4.8-12.65-9.69-12.55");
}

.pplze2bny {
  d: path("m67.97 43.62l-5.07-2.3S54.86 59.67 50.79 66c-4.08 6.33-11.5 16.3-11.5 16.3c.01 8.53-3.9 12.02 1.39 17.95c.35.4.72.75 1.08 1.08c3.39-4.07 8.99-12.02 13.19-17.98C66.3 67.24 67.97 43.62 67.97 43.62");
}

.pu-7lsbti {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M76.07 26.84a.3.3 0 0 0-.09-.02l-1.98.04c-.03 0-.06.01-.09.02c-.18.08-.27.26-.18.46s.5.75 1.29.73c.8-.02 1.18-.58 1.26-.78s-.03-.38-.21-.45");
}

.qv4ka_bia {
  fill: none;
  d: path("M103.54 24.36c-1.01-2.75-5.95-10.64-5.95-10.64l-5.74 2.76l2.28 9.86l-10.27 8.55a34.9 34.9 0 0 0-12.95-.52c-2.94-.22-11.3-.12-14.46 7.57l-4.58 10.9l-3.71 1.29c-1.03 2.15 2.35 4.09 4.5 5.11s4 .23 5.76-2.04c1.05-1.36 3.49-5.17 5.27-8c.4 3.03.68 6.73.7 11.23l8.33 4.01l10.14.43c3.7-8.37 5.61-14.74 6.58-19.25c3.35-3.78 12.03-13.6 13.15-15.16c1.38-1.92 1.96-3.35.95-6.1");
  opacity: var(--svg-opacity--0-29, 0.29);
}

.r5vbxk1ae {
  stop-color: var(--svg-color--1e88e5, #1e88e5);
}

.rj04jfnia {
  stop-color: var(--svg-color--42a5f5, #42a5f5);
}

.tx-hj233l {
  d: path("M92.68 24.92c-.14-.93-1.91-15.14-5.23-15.88c0 0-1.76.02-3.56.18c-1.42.05-2.36-.33-2.63-1.22c-.33-.68.01-2.2.58-3.9c.57-1.71 1.59-1.92 2.4-1.94c1.57-.04 4.25 1.55 7.93 4.73c7.08 6.12 10.95 15.35 10.95 15.35c-.13 0-4.69 6.23-10.44 2.68");
}

.w3ewgyb1k {
  fill: var(--svg-color--ed4132, #ed4132);
  d: path("M75.21 38.37s.47-4.91 3.79-6.1s10.76-2.29 10.76-2.29s-2.33 4.56-4.13 6c-3.8 3.03-10.42 2.39-10.42 2.39");
}

.wi8v79m_m {
  stop-color: var(--svg-color--db4437, #db4437);
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.x11b2bb6t {
  fill: none;
  d: path("M92.68 24.92c-.14-.93-1.91-15.14-5.23-15.88c0 0-1.76.02-3.56.18c-1.42.05-2.36-.33-2.63-1.22c-.33-.68.01-2.2.58-3.9c.57-1.71 1.59-1.92 2.4-1.94c1.57-.04 4.25 1.55 7.93 4.73c7.08 6.12 10.95 15.35 10.95 15.35c-.13 0-4.69 6.23-10.44 2.68");
  opacity: var(--svg-opacity--0-29, 0.29);
}

.y3jqodvht {
  fill: var(--svg-color--543930, #543930);
  d: path("M74.49 8.81q-.015 0 0 0q-.015 0 0 0c-12.79.4-9.79 14.93-9.79 14.93s.61 1.49.89 2.15c.04.09.18.08.2-.02c.24-1.23 1.11-5.58 1.57-6.91c.27-.78 1.06-1.25 1.88-1.13c1.26.19 3.26.42 5.46.37h.04c2.2-.06 4.19-.39 5.44-.65c.81-.17 1.63.26 1.94 1.03c.53 1.3 1.61 5.58 1.92 6.81c.03.1.17.11.2.01l.78-2.18c.01-.01 2.25-14.67-10.53-14.41");
}

.y73_33btq {
  fill: var(--svg-color--404040, #404040);
}

.ya4pnpsxo {
  d: path("M85.03 23.21s2.24-14.67-10.55-14.4l-.58.03c-.38.03-.75.06-1.1.12h-.01c-.03 0-.05.01-.07.01C62 10.6 64.71 23.74 64.71 23.74l.89 2.14c.04.09.18.08.2-.02c.24-1.24 1.11-5.58 1.57-6.9c.27-.78 1.06-1.25 1.88-1.13c1.26.19 3.26.42 5.46.37h.04c2.2-.06 4.19-.39 5.44-.65c.81-.17 1.63.26 1.94 1.03c.53 1.3 1.62 5.61 1.93 6.82c.03.1.16.11.2.01c.23-.67.77-2.2.77-2.2");
}

.yac5kp3-q {
  stop-color: var(--svg-color--d32f2f, #d32f2f);
}

.yor6rcbnf {
  d: path("M68.81 44.72s2.96-1.99 8.73-2.2s8.15 2.33 8.15 2.33l-8.48 9.12z");
  opacity: var(--svg-opacity--0-42, 0.42);
}

.z-k93uvrs {
  d: path("M52.68 82.85s-5.54 5.15-5.95 7.46c-.68 3.83 2.56 7.37 4.24 6c3.65-2.96 4.64-6.63 6.45-9.29c1.8-2.66-2.34-6.6-4.74-4.17");
}

</style>
