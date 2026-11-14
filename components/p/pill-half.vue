<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkxwd0hwh"/><path class="jbgj_xbos"/><path class="yo4ia5pve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pill-half" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbgj_xbos {
  d: path("M2.75 10v3.5a7.75 4 0 0 0 7.75 4V14m3-8a7.75 4 0 0 1 0 8Z");
}

.nkxwd0hwh {
  d: path("M10.5 6a7.75 4 0 0 0 0 8Z");
}

.yo4ia5pve {
  d: path("M21.25 10v3.5a7.75 4 0 0 1-7.75 4V14");
}

</style>
