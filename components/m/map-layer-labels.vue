<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nt6z33jcl"/><path class="v2jzgr56j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-layer-labels" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nt6z33jcl {
  d: path("M13.587 3h4.788A2.625 2.625 0 0 1 21 5.625v4.788a2.63 2.63 0 0 1-.769 1.856l-6.875 6.875a2.625 2.625 0 0 1-3.712 0l-4.788-4.788a2.625 2.625 0 0 1 0-3.712l6.875-6.875A2.63 2.63 0 0 1 13.587 3");
}

.v2jzgr56j {
  d: path("M15 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
