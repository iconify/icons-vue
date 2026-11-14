<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6h_wdbij"/><path class="wxeg-rbdk"/><path class="ue4e1nzzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-refresh" /></template>
<style>
.j6h_wdbij {
  d: path("M8.723 18.115L3 20.5V6l6-2.5L15 6l6-2.5v8.8M9 3.5v14.3M15 6v5.7");
}

.ue4e1nzzz {
  d: path("m12.5 18.25l1.5-1.5l1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxeg-rbdk {
  d: path("M14 17.5a3.5 3.5 0 1 1 3.5 3.5");
}

</style>
