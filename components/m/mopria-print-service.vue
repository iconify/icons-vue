<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hnm_t_buh"/><path class="c_sg0kb6m"/><path class="myt1kubwe"/><path class="q5wdeccve"/><ellipse class="lq6_vs4sm"/><ellipse class="hxibyrb-a"/><ellipse class="ym4l-ybwp"/><ellipse class="ph9pdyb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mopria-print-service" /></template>
<style>
.c_sg0kb6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.653 28.418h4.916c.604 0 1.09.42 1.09.94v1.616c0 .52-.486.939-1.09.939h-4.916m-.004-5.349h4.517c.842 0 1.518-.678 1.518-1.52V14.258c0-.841-.676-1.52-1.518-1.52H8.836c-.841 0-1.519.679-1.519 1.52v10.788c0 .841.678 1.52 1.52 1.52h4.945m.002-1.76H11.56c-.602 0-1.087-.42-1.087-.94V21.78c0-.52.485-.938 1.087-.938h24.88c.602 0 1.087.418 1.087.938v2.086c0 .52-.485.94-1.087.94h-1.787m2.298-10.132h.013a2.068 2.068 0 1 1-2.07 2.07v-.001c0-1.139.919-2.063 2.057-2.069");
}

.hnm_t_buh {
  width: 24.842px;
  height: 7.238px;
  x: 11.58px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

.hxibyrb-a {
  cx: 28.32px;
  cy: 26.988px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.84px;
  ry: 1.545px;
}

.lq6_vs4sm {
  cx: 19.505px;
  cy: 29.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.868px;
  ry: 1.529px;
}

.myt1kubwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.847 22.863h18.742c.587 0 1.064.519 1.064 1.158v17.32c0 .64-.477 1.159-1.064 1.159H14.846c-.588 0-1.064-.519-1.064-1.158v-17.32c0-.64.476-1.159 1.064-1.159");
}

.ph9pdyb5z {
  cx: 27.737px;
  cy: 33.453px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.023px;
  ry: 1.971px;
}

.q5wdeccve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.783 31.913H8.474c-.641 0-1.158-.419-1.158-.939v-1.617c0-.52.517-.938 1.158-.938h5.309m2.483 9.031h15.688m-15.688 2.56h15.688");
}

.ym4l-ybwp {
  cx: 22.338px;
  cy: 23.755px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 0.892px;
}

</style>
