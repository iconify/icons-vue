<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ks0o4wbwg"/><path class="jy7mjxbua"/><path class="t_aandbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:virtual-staging" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy7mjxbua {
  d: path("M8 13v-2.5A1.5 1.5 0 0 1 9.5 9h5a1.5 1.5 0 0 1 1.5 1.5V13");
}

.ks0o4wbwg {
  d: path("M5.125 3h13.75A2.625 2.625 0 0 1 21.5 5.625v12.75A2.625 2.625 0 0 1 18.875 21H5.125A2.625 2.625 0 0 1 2.5 18.375V5.625A2.625 2.625 0 0 1 5.125 3");
}

.t_aandbkn {
  d: path("M6 17.5v-3a1.5 1.5 0 0 1 3 0v.5h6v-.5a1.5 1.5 0 0 1 3 0v3Z");
}

</style>
