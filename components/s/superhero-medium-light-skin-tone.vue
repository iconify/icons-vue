<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGQL8n4c7h" x1="79.567" x2="51.086" y1="78.962" y2="40.814" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="ezcsz113k"/></linearGradient><path fill="url(#SVGQL8n4c7h)" class="fr1th1bnm"/><radialGradient id="SVGVA5KL9hS" cx="74.878" cy="64.629" r="18.579" gradientTransform="rotate(200.578 -5.617 80.714)scale(-1 1.9378)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".999" class="gjuor2bpt"/></radialGradient><path fill="url(#SVGVA5KL9hS)" class="c3o6p_bbl"/><linearGradient id="SVG938Hod5x" x1="44.406" x2="59.099" y1="72.898" y2="47.53" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".999" class="gjuor2bpt"/></linearGradient><path fill="url(#SVG938Hod5x)" class="pplze2bny"/><linearGradient id="SVGpMo8J76x" x1="76.007" x2="75.835" y1="86.58" y2="66.902" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rj04jfnia"/><stop offset="1" class="r5vbxk1ae"/></linearGradient><path fill="url(#SVGpMo8J76x)" class="c9f8lgbak"/><path class="qv4ka_bia"/><linearGradient id="SVGlwb2gdTv" x1="50.366" x2="43.808" y1="75.374" y2="89.607" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="wi8v79m_m"/></linearGradient><path fill="url(#SVGlwb2gdTv)" class="h_dav37mp"/><path class="a-v9uefku"/><linearGradient id="SVGEb8ZfbUI" x1="55.129" x2="50.129" y1="43.972" y2="36.222" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="l163gnb3q"/><stop offset=".841" class="cqr7j4bgr"/></linearGradient><path fill="url(#SVGEb8ZfbUI)" class="z-k93uvrs"/><linearGradient id="SVGHtA1BbSN" x1="69.79" x2="60.641" y1="55.927" y2="35.386" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rj04jfnia"/><stop offset="1" class="r5vbxk1ae"/></linearGradient><path fill="url(#SVGHtA1BbSN)" class="d3k9k1bej"/><path class="av9i0v24v"/><linearGradient id="SVGUsxvhblt" x1="62.701" x2="84.321" y1="65.551" y2="60.826" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="yac5kp3-q"/><stop offset=".23" class="ai1a8abib"/><stop offset=".742" class="ai1a8abib"/><stop offset="1" class="yac5kp3-q"/></linearGradient><path fill="url(#SVGUsxvhblt)" class="led8d0bhz"/><path class="itxgn3vuq"/><path class="hy1ry5b_q"/><path class="d925exa8n"/><linearGradient id="SVG6DoXccGG" x1="77.247" x2="77.247" y1="83.257" y2="73.402" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="dl-6blb5x"/><stop offset="1" class="g3c_jbvil"/></linearGradient><path fill="url(#SVG6DoXccGG)" class="yor6rcbnf"/><linearGradient id="SVGWzkfQbdy" x1="66.098" x2="43.784" y1="27.623" y2="5.309" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="ezcsz113k"/></linearGradient><path fill="url(#SVGWzkfQbdy)" class="f936r0mwr"/><path class="crlr_4g4j"/><path class="w3ewgyb1k"/><path class="jqb568bki"/><linearGradient id="SVGiJkax1SQ" x1="98.368" x2="84.559" y1="104.084" y2="124.97" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cqr7j4bgr"/><stop offset=".529" class="g19bbhpmg"/><stop offset="1" class="wi8v79m_m"/></linearGradient><path fill="url(#SVGiJkax1SQ)" class="tx-hj233l"/><path class="x11b2bb6t"/><path class="f5q8-ub-l"/><radialGradient id="SVGKDrZSd7j" cx="99.569" cy="93.17" r="6.657" gradientTransform="rotate(-2.287 -303.278 550.178)scale(1 .4912)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGKDrZSd7j)" class="rt8ejo4op"/><radialGradient id="SVGghvt0cYK" cx="93.012" cy="94.16" r="1.968" gradientTransform="rotate(152.633 94.316 48.447)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGghvt0cYK)" class="wv8dwsjkq"/><radialGradient id="SVGPyda6bxp" cx="98.111" cy="99.726" r="8.642" gradientTransform="matrix(-.1144 -.9934 .828 -.0953 8.966 130.45)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGPyda6bxp)" class="mxd2aqbzj"/><radialGradient id="SVGsIvuIcgf" cx="68.909" cy="99.726" r="8.642" gradientTransform="matrix(.0347 -.9994 -.8329 -.029 149.791 95.688)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGsIvuIcgf)" class="syiror80h"/><radialGradient id="SVGByPxQILv" cx="70.367" cy="93.17" r="6.657" gradientTransform="rotate(177.713 69.845 -7.669)scale(1 -.4912)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGByPxQILv)" class="ulvt32b6p"/><radialGradient id="SVGwaEdcmDE" cx="63.81" cy="94.16" r="1.968" gradientTransform="rotate(202.786 -3.825 36.866)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGwaEdcmDE)" class="n0q8y0qru"/><path class="ufikw0x_n"/><path class="v9lzvtt4a"/><g class="qp89kubki"><ellipse transform="rotate(-1.564 70.155 24.466)" class="bk6zu_3lz"/><ellipse transform="rotate(-1.564 79.425 24.216)" class="xxctnnqtq"/></g><path class="hoif3-59c"/><path class="s9_s012wy"/><path class="icbopgbav"/><path class="eia0m84qq"/><radialGradient id="SVGOXH12hNb" cx="79.629" cy="104.284" r="10.13" gradientTransform="matrix(.3454 .9385 .6963 -.2562 -20.46 -29.068)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGOXH12hNb)" class="o11zclrav"/><radialGradient id="SVGzw8OcdTG" cx="69.753" cy="115.329" r="2.656" gradientTransform="matrix(.8995 .437 .5182 -1.0665 -53.159 100.819)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGzw8OcdTG)" class="klrq1ohlp"/><radialGradient id="SVGZo5HkefX" cx="151.972" cy="68.119" r="8.165" gradientTransform="matrix(-.9528 -.3566 -.1969 .5367 233.682 30.527)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGZo5HkefX)" class="a5c4v7oqp"/><radialGradient id="SVGRDIvQdsE" cx="68.687" cy="112.906" r="2.438" gradientTransform="matrix(.9992 -.0399 -.0489 -1.2223 5.266 151.515)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGRDIvQdsE)" class="ldejh1zrf"/><radialGradient id="SVGQ7FirbKx" cx="68.351" cy="108.603" r="4.572" gradientTransform="rotate(12.773 386.617 668.43)scale(-1 .9359)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGQ7FirbKx)" class="yqgxlh13q"/><radialGradient id="SVGCEKCGdlU" cx="67.266" cy="104.189" r="4.8" gradientTransform="matrix(.9953 .0966 .1358 -1.3986 -13.795 158.75)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGCEKCGdlU)" class="d5q54qkqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:superhero-medium-light-skin-tone" /></template>
<style>
.a-v9uefku {
  fill: none;
  d: path("M41.61 38.62c.59-1.08 2.44-1.82 3.77-2.23c.81-.25 1.67.17 1.99.94l1.97 4.72c.24.58.13 1.25-.29 1.73l-1.85 2.08c.68.92 1.53 1.66 2.51 2.25c1.67 1.01 3.34.97 3.51 1.11c2.12 1.71 3.7 3.71 2.46 6.99c-1.23 3.26-5.47 2.26-5.47 2.26s-4.35-3.06-7.15-9.7c-.91-2.13-2.68-7.91-1.45-10.15");
  opacity: var(--svg-opacity--0-29, 0.29);
}

.a5c4v7oqp {
  d: path("M78.41 8.3c2.1.48 3.16 1.5 3.55 2.9c.12.41.39 4.27-7.17.17c-2.81-1.53-2.1-2.58-1.79-2.71c1.25-.5 3.06-.9 5.41-.36");
}

.ai1a8abib {
  stop-color: var(--svg-color--f44336, #f44336);
}

.atqdr-9uk {
  stop-color: var(--svg-color--bfa055, #bfa055);
}

.av9i0v24v {
  fill: var(--svg-color--212121, #212121);
  d: path("m61.24 63.89l2-3.26c.28-.63 1-.89 1.58-.56c6.62 3.78 10.14 4.79 17.67 4.34c.69-.04 1.26.58 1.21 1.33l-.26 3.51s-2.76 1.56-11.19-.23c-5.98-1.27-11.01-5.13-11.01-5.13");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.bk6zu_3lz {
  cx: 70.15px;
  cy: 24.47px;
  rx: 1.39px;
  ry: 1.44px;
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

.d5q54qkqi {
  d: path("M63.17 16.91c-.65.62-1.5 1.99-.77 3.62c.55 1.23 2.37 1.7 2.37 1.7s.36.1.55.09l.17-6.24c-.86.03-1.68.33-2.2.72c.01 0-.12.1-.12.11");
}

.d925exa8n {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("M78.21 44.58c1.89 0 3.28.34 4.25.71l-5.23 5.62l-4.95-5.45c1.27-.4 3.06-.79 5.33-.87c.21-.01.4-.01.6-.01m0-2.07c-.22 0-.44 0-.67.01c-5.77.21-8.73 2.2-8.73 2.2l8.4 9.25l8.48-9.12c-.01 0-2.19-2.34-7.48-2.34");
}

.dl-6blb5x {
  stop-color: var(--svg-color--0d47a1, #0d47a1);
  stop-opacity: 0;
}

.eia0m84qq {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M85.71 13.6c-.74-1.02-2.35-2.37-3.74-2.4c-.28-1.33-1.76-2.41-3.16-2.8c-3.81-1.04-6.2.39-7.48 1.16c-.27.16-1.99 1.21-3.25.56c-.79-.41-.82-1.6-.82-1.6s-2.39 1.02-1.45 3.56c-.83.07-1.91.46-2.44 1.65c-.63 1.42-.34 2.57-.12 3.12c-.69.64-1.54 1.97-.86 3.62c.52 1.25 2.4 1.75 2.4 1.75c-.04 2.28.44 3.66.69 4.22c.04.1.18.08.21-.02c.24-1.14 1.04-5.1.92-5.79c0 0 3.2-.77 6.18-3.15c.61-.49 1.27-.91 1.98-1.22c3.8-1.69 4.71.9 4.71.9s2.65-.62 3.61 3.06c.36 1.38.65 3.6.89 5.15c.02.11.17.13.21.02c.25-.63.74-1.88.82-3.14c.03-.44 1.19-1.07 1.63-2.98c.54-2.54-.39-4.93-.93-5.67");
}

.ezcsz113k {
  stop-color: var(--svg-color--ed4132, #ed4132);
}

.f5q8-ub-l {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M84.87 29.2c-.38-.63.05-1.31.78-2.15c1.17-1.34 2.38-4.38 1.03-7.37c.01-.02-.26-.52-.26-.54h-.51c-.16-.02-5.76.19-11.36.42c-5.6.22-11.19.46-11.35.49c0 0-.73.58-.72.6c-1.12 3.09.34 6.02 1.61 7.26c.8.78 1.28 1.42.95 2.08c-.32.64-1.34.77-1.34.77s.26.63.84.95c.54.3 1.19.35 1.64.34c0 0 1.84 2.35 6.41 2.17l2.54-.1l2.54-.1c4.57-.18 6.22-2.67 6.22-2.67c.45-.03 1.09-.13 1.6-.47c.56-.37.77-1.02.77-1.02s-1.02-.04-1.39-.66");
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

.gjuor2bpt {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0;
}

.h_dav37mp {
  d: path("M41.61 38.62c.59-1.08 2.44-1.82 3.77-2.23c.81-.25 1.67.17 1.99.94l1.97 4.72c.24.58.13 1.25-.29 1.73l-1.85 2.08c.68.92 1.53 1.66 2.51 2.25c1.67 1.01 3.34.97 3.51 1.11c2.12 1.71 3.7 3.71 2.46 6.99c-1.23 3.26-5.47 2.26-5.47 2.26s-4.35-3.06-7.15-9.7c-.91-2.13-2.68-7.91-1.45-10.15");
}

.hoif3-59c {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M77.24 29.42c-.88.56-3.83.64-4.74.13c-.52-.29-1.04.19-.81.65c.22.45 1.86 1.48 3.25 1.44s2.95-1.15 3.14-1.62c.2-.46-.33-.92-.84-.6");
}

.hy1ry5b_q {
  fill: var(--svg-color--e53935, #e53935);
  d: path("M70.48 45.02c1.28-.56 3.66-1.34 7.09-1.47c.22-.01.43-.01.63-.01c3.09 0 4.98.84 5.95 1.43l-6.94 7.46z");
}

.icbopgbav {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M72.21 21.79c-.27-.34-.9-.84-2.09-.81s-1.79.56-2.04.92c-.11.16-.08.34.01.44c.08.1.3.19.55.1s.72-.35 1.52-.38c.8-.02 1.29.22 1.54.3s.47-.02.54-.13a.38.38 0 0 0-.03-.44m9.28-.25c-.27-.34-.9-.84-2.09-.81s-1.79.56-2.04.92c-.11.16-.08.34.01.44c.08.1.3.19.55.1s.72-.35 1.52-.38c.8-.02 1.29.22 1.54.3s.47-.02.54-.13c.06-.11.09-.29-.03-.44");
}

.itxgn3vuq {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("m75.57 66.99l-2.31 1.53c-.46.3-1.07.18-1.37-.28l-1.53-2.31a.985.985 0 0 1 .28-1.37l2.31-1.53a.985.985 0 0 1 1.37.28l1.53 2.31c.3.45.18 1.06-.28 1.37");
}

.jqb568bki {
  fill: var(--svg-color--212121, #212121);
  d: path("M57.13 40.53s3.26-2.94 8.22-1.75c7.14 1.71 9.86-.41 9.86-.41s5.25 1.89 10.22-.5c3.41-1.64 4.34-7.89 4.34-7.89L88.6 31.3s-4.38 4.77-8.74 6.06c-3.19.95-4.64 1.01-4.64 1.01s-11.76-4.03-14.44-2.91s-3.65 5.07-3.65 5.07");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.klrq1ohlp {
  d: path("M72.13 9.1c-.31.16-.57.32-.81.46c-.27.16-1.99 1.21-3.25.56c-.78-.4-.82-1.55-.82-1.6c-.33.46-1.26 3.69 1.84 3.78c1.34.04 2.11-1.16 2.56-2.16c.15-.37.41-.9.48-1.04");
}

.l163gnb3q {
  stop-color: var(--svg-color--851f10, #851f10);
}

.l1arbqe-k {
  stop-color: var(--svg-color--bfa055, #bfa055);
  stop-opacity: 0;
}

.ldejh1zrf {
  d: path("M67.24 8.52s-.01 0-.02.01c-.26.12-2.3 1.17-1.43 3.54l2.22.27c-2.03-1.9-.76-3.82-.77-3.82c.01 0 0 0 0 0");
}

.led8d0bhz {
  d: path("M83.08 68.94c-8.48.45-13.79-1.08-21.19-5.01c-.58-.31-.81-1.02-.53-1.62l1.19-2.52c.3-.63 1.07-.89 1.69-.56c7.09 3.78 10.86 4.78 18.94 4.34c.74-.04 1.36.59 1.29 1.33l-.23 2.9c-.05.62-.55 1.11-1.16 1.14");
}

.mxd2aqbzj {
  d: path("M86.68 19.68c1.32 2.89.18 5.97-.96 7.3c-.16.18-.82.89-.96 1.44c0 0-2.86-3.67-3.76-5.86c-.18-.44-.35-.9-.39-1.37c-.03-.36.01-.78.2-1.1c.24-.38 5.71-.71 5.71-.71c.01 0 .16.3.16.3");
}

.n0q8y0qru {
  d: path("M66.16 30.89c1.14-1.9-1.58-2.48-1.58-2.48c.49.56.72 1.06.47 1.58c-.32.64-1.34.77-1.34.77s1.44 1.19 2.45.13");
}

.o11zclrav {
  d: path("M84.96 22.27c.03-.44 1.19-1.07 1.63-2.98c.05-.2.08-.41.12-.62c.32-2.32-.51-4.4-1-5.07c-.68-.94-2.11-2.16-3.42-2.37c-.11-.01-.22-.02-.33-.02c0 0 .12.61-.11 1.1c-.29.64-.94.82-.94.82c3.54 3.27 3.41 6.12 4.05 9.14");
}

.pplze2bny {
  d: path("m67.97 43.62l-5.07-2.3S54.86 59.67 50.79 66c-4.08 6.33-11.5 16.3-11.5 16.3c.01 8.53-3.9 12.02 1.39 17.95c.35.4.72.75 1.08 1.08c3.39-4.07 8.99-12.02 13.19-17.98C66.3 67.24 67.97 43.62 67.97 43.62");
}

.qp89kubki {
  fill: var(--svg-color--5d4037, #5d4037);
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

.rt8ejo4op {
  d: path("m75.13 34.13l-.11-2.68l8.09-.97l.78.88s-1.65 2.49-6.22 2.67z");
}

.s9_s012wy {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M75.76 26.87a.3.3 0 0 0-.09-.02l-2 .06q-.045 0-.09.03c-.18.08-.27.27-.18.47s.5.75 1.3.72c.8-.02 1.18-.59 1.26-.79c.08-.22-.02-.41-.2-.47");
}

.syiror80h {
  d: path("M62.48 20.65c-1.09 2.99.3 5.97 1.54 7.2c.17.17.89.82 1.07 1.36c0 0 2.56-3.89 3.28-6.14c.14-.45.28-.92.28-1.4c0-.36-.07-.78-.29-1.08c-.27-.36-.56-.25-.99-.23c-.82.03-4.41-.03-4.69-.02c0-.01-.2.31-.2.31");
}

.tx-hj233l {
  d: path("M92.68 24.92c-.14-.93-1.91-15.14-5.23-15.88c0 0-1.76.02-3.56.18c-1.42.05-2.36-.33-2.63-1.22c-.33-.68.01-2.2.58-3.9c.57-1.71 1.59-1.92 2.4-1.94c1.57-.04 4.25 1.55 7.93 4.73c7.08 6.12 10.95 15.35 10.95 15.35c-.13 0-4.69 6.23-10.44 2.68");
}

.ufikw0x_n {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("m75.01 31.28l-3.22.09l.09 2.5c0 3.16 3.36 4.5 3.36 4.5s3.07-1.65 3.07-4.55l-.09-2.62zm7.42-9.79l-2.08.06l-11.26.31l-2.08.06c-1.66.05-2.98 1.53-2.93 3.3s1.45 3.18 3.11 3.14l2.08-.06l11.26-.31l2.08-.06c1.66-.05 2.98-1.53 2.93-3.3s-1.45-3.18-3.11-3.14");
}

.ulvt32b6p {
  d: path("m75.14 34.13l-.11-2.68l-8.14-.32l-.7.94s1.84 2.35 6.41 2.17z");
}

.v9lzvtt4a {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M74.38 10.32c-4.91.13-9.31 5.51-9.1 13.06c.21 7.51 4.99 11.1 9.76 10.97s9.35-3.97 9.15-11.49c-.22-7.55-4.91-12.67-9.81-12.54");
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

.wv8dwsjkq {
  d: path("M83.82 30.19c-1.29-1.8 1.38-2.59 1.38-2.59c-.45.6-.64 1.12-.34 1.61c.37.61 1.4.66 1.4.66s-1.34 1.29-2.44.32");
}

.x11b2bb6t {
  fill: none;
  d: path("M92.68 24.92c-.14-.93-1.91-15.14-5.23-15.88c0 0-1.76.02-3.56.18c-1.42.05-2.36-.33-2.63-1.22c-.33-.68.01-2.2.58-3.9c.57-1.71 1.59-1.92 2.4-1.94c1.57-.04 4.25 1.55 7.93 4.73c7.08 6.12 10.95 15.35 10.95 15.35c-.13 0-4.69 6.23-10.44 2.68");
  opacity: var(--svg-opacity--0-29, 0.29);
}

.xxctnnqtq {
  cx: 79.42px;
  cy: 24.21px;
  rx: 1.39px;
  ry: 1.44px;
}

.yac5kp3-q {
  stop-color: var(--svg-color--d32f2f, #d32f2f);
}

.yor6rcbnf {
  d: path("M68.81 44.72s2.96-1.99 8.73-2.2s8.15 2.33 8.15 2.33l-8.48 9.12z");
  opacity: var(--svg-opacity--0-42, 0.42);
}

.yqgxlh13q {
  d: path("m67.17 12.24l-1.37-.16c-.05 0-.24.03-.33.04c-.76.14-1.66.57-2.1 1.61c-.48 1.12-.43 2.06-.26 2.68c.05.21.15.44.15.44s.65-.67 2.26-.77z");
}

.z-k93uvrs {
  d: path("M52.68 82.85s-5.54 5.15-5.95 7.46c-.68 3.83 2.56 7.37 4.24 6c3.65-2.96 4.64-6.63 6.45-9.29c1.8-2.66-2.34-6.6-4.74-4.17");
}

</style>
