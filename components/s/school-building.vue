<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1k5qcbmf"/><path class="ub_-pcbch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:school-building" /></template>
<style>
.ub_-pcbch {
  d: path("M10.25 20.5v-3.25a1.75 1.75 0 0 1 3.5 0v3.25M12 12h.01m-7.26 4h.01m14.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1k5qcbmf {
  d: path("M2.5 20.5v-8H7v-2l5-4l5 4v2h4.5v8Zm9.5-14v-4l3.5 1l-3.5 1");
}

</style>
