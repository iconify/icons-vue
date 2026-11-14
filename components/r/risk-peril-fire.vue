<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h98gxob2v"/><path class="wuaj8woci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:risk-peril-fire" /></template>
<style>
.h98gxob2v {
  d: path("m13.856 4.356l5.788 5.788a2.625 2.625 0 0 1 0 3.712l-5.788 5.788a2.625 2.625 0 0 1-3.712 0l-5.788-5.788a2.625 2.625 0 0 1 0-3.712l5.788-5.788a2.625 2.625 0 0 1 3.712 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wuaj8woci {
  d: path("M12 17c-1.75 0-2.75-1-2.75-2.25c0-1.5 1.75-2 2-3.75c.75.5 1 1.25 1 2c.75-.25 1.25-1 1.5-1.5c.75 1 1 2 1 3.25S13.75 17 12 17");
}

</style>
