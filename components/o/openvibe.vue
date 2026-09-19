<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="my4zh0bld"/><ellipse class="ozdw0abim"/><ellipse class="s2up7nhph"/><path class="jz65g6b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openvibe" /></template>
<style>
.jz65g6b5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.888 31.453s1.272 1.55 2.15 1.525c.816-.023 1.916-1.525 1.916-1.525");
}

.my4zh0bld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.93 35.808c-.278-1.193 8.302-.293 8.302-.293S9.35 34.93 6.915 33.46c-1.578-.953-1.867-4.482-.712-4.908c.894-.329 2.451 1.407 4.126 2.114c.75.316 2.986 1.325 3.148.017C10.687 21.264 8.9 7.84 24.042 7.854C40.1 7.871 36.165 23.19 34.204 31.442c-.039.162 5.853-3.987 7.16-3.142c4.343 2.805-4.924 6.3-8.424 7.24c-.543.145 4.648.406 6.898.305c.327-.014-.353 1.9-2.121 3.214c-4.18 3.103-13.617-1.775-13.617-1.775S8.986 44.616 6.93 35.808");
}

.ozdw0abim {
  cx: 17.982px;
  cy: 27.78px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.678px;
  ry: 3.145px;
}

.s2up7nhph {
  cx: 30.076px;
  cy: 27.78px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.678px;
  ry: 3.145px;
}

</style>
