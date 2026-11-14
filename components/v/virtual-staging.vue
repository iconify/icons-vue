<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="jy7mjxbua"/><path class="t_aandbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:virtual-staging" /></template>
<style>
.jy7mjxbua {
  d: path("M8 13v-2.5A1.5 1.5 0 0 1 9.5 9h5a1.5 1.5 0 0 1 1.5 1.5V13");
}

.t_aandbkn {
  d: path("M6 17.5v-3a1.5 1.5 0 0 1 3 0v.5h6v-.5a1.5 1.5 0 0 1 3 0v3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

</style>
