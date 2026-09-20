<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGdNVwwe0k" x1="64" x2="64" y1="32.312" y2="4.301" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="ce2-qdwyj"/><stop offset=".225" class="ghh99pe3l"/><stop offset=".635" class="ha_czob6z"/><stop offset="1" class="k3lw9kb6h"/></linearGradient><path fill="url(#SVGdNVwwe0k)" class="p5bfb0blh"/><path class="idc-yp-yq"/><linearGradient id="SVGPzuSjc3t" x1="64" x2="64" y1="16.319" y2="34.552" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="sl8ua6bht"/><stop offset="1" class="b8rop1bve"/></linearGradient><path fill="url(#SVGPzuSjc3t)" class="ez_2t5bdi"/><path class="x82xblonc"/><path class="sj6ll9bld"/><g class="d2ol71wkq"><ellipse class="xm_cxnkcf"/><ellipse class="qi4mcqr9e"/></g><path class="f4vbxhbgs"/><path class="k42o46bem"/><path class="gcna5fi1z"/><radialGradient id="SVGvREjNeWa" cx="63.983" cy="80.901" r="38.093" gradientTransform="matrix(1 0 0 -1.1282 0 138.37)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGvREjNeWa)" class="qu5nm8boy"/><path class="ut66tab8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-office-worker-dark-skin-tone" /></template>
<style>
.b8rop1bve {
  stop-color: var(--svg-color--dadada, #dadada);
}

.ce2-qdwyj {
  stop-color: var(--svg-color--e3f2fd, #e3f2fd);
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.ez_2t5bdi {
  d: path("M75.02 91.38H52.98l-6.59 7.12l9.48 14.69L64 103.15l8.13 10.04l9.48-14.69z");
}

.f4vbxhbgs {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M67.86 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.3-.71-.05-1.37-.69-1.63");
}

.g00j4bcaa {
  stop-color: var(--svg-color--444140, #444140);
}

.gcna5fi1z {
  fill: var(--svg-color--232020, #232020);
  d: path("M64 4.03h-.04c-45.43.24-36.12 52.14-36.12 52.14s2.04 5.35 2.97 7.71c.13.34.63.3.71-.05c.97-4.34 4.46-19.73 6.22-24.41a6.075 6.075 0 0 1 6.79-3.83c4.45.81 11.55 1.81 19.37 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.75 4.66 5.22 19.96 6.2 24.36c.08.36.58.39.71.05l2.98-7.67c.02.01 9.33-51.89-36.11-52.13");
}

.ghh99pe3l {
  stop-color: var(--svg-color--d6ecfc, #d6ecfc);
}

.ha_czob6z {
  stop-color: var(--svg-color--b4dbfb, #b4dbfb);
}

.idc-yp-yq {
  fill: var(--svg-color--1565c0, #1565c0);
  d: path("m66.28 113.27l2.37-4.65l-4.65-5.47l-4.65 5.47l2.37 4.65l-2.87 10.69h10.3z");
}

.k3lw9kb6h {
  stop-color: var(--svg-color--90caf9, #90caf9);
}

.k42o46bem {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.p5bfb0blh {
  d: path("M64.14 96H64c-25.65.03-52 7.1-52 24.99v2.95h104v-2.95C116 104.12 89.9 96 64.14 96");
}

.qi4mcqr9e {
  cx: 80.44px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.qpo2vg_rh {
  stop-color: var(--svg-color--444140, #444140);
  stop-opacity: 0;
}

.qu5nm8boy {
  d: path("M100.13 56.17S109.44 4.27 64 4.03h-.04c-.71 0-1.4.02-2.08.05c-1.35.06-2.66.16-3.92.31h-.04c-.09.01-.17.03-.26.04c-38.24 4.81-29.82 51.74-29.82 51.74l2.98 7.68c.13.34.62.31.7-.05c.98-4.39 4.46-19.71 6.22-24.37a6.075 6.075 0 0 1 6.79-3.83c4.45.81 11.55 1.81 19.37 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.76 4.68 5.25 20.1 6.21 24.42c.08.36.57.39.7.05c.95-2.36 3-7.73 3-7.73");
}

.sj6ll9bld {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M64 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S97.52 83.1 97.52 56.46c0-26.78-16.12-45.39-33.52-45.39");
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.ut66tab8e {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M40.01 50.72c2.99-4.23 9.78-4.63 13.67-1.48c.62.5 1.44 1.2 1.68 1.98c.4 1.27-.82 2.26-2.01 1.96c-.76-.19-1.47-.6-2.22-.83c-1.37-.43-2.36-.55-3.59-.55c-1.82-.01-2.99.22-4.72.92c-.71.29-1.29.75-2.1.41c-.93-.38-1.28-1.57-.71-2.41m46.06 2.41c-.29-.13-.57-.29-.86-.41c-1.78-.74-2.79-.93-4.72-.92c-1.7.01-2.71.24-4.04.69c-.81.28-1.84.98-2.74.71c-1.32-.4-1.28-1.84-.56-2.76c.86-1.08 2.04-1.9 3.29-2.44c2.9-1.26 6.44-1.08 9.17.55c.89.53 1.86 1.26 2.4 2.18c.78 1.3-.4 3.03-1.94 2.4");
}

.x82xblonc {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M64 84.33h-9.08v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98zm27.33-33.9H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.81-11.41-10.7-11.41");
}

.xm_cxnkcf {
  cx: 47.56px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

</style>
