<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqgzs9b2w"/><path class="kkrruc_3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shopping-list" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkrruc_3t {
  d: path("M8.75 5.5zA1.25 1.25 0 0 1 10 6.75A1.25 1.25 0 0 1 8.75 8A1.25 1.25 0 0 1 7.5 6.75A1.25 1.25 0 0 1 8.75 5.5m0 5.25zA1.25 1.25 0 0 1 10 12a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 7.5 12a1.25 1.25 0 0 1 1.25-1.25m0 5.25zA1.25 1.25 0 0 1 10 17.25a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 8.75 16m4-9.25h3.75M12.75 12h3.75m-3.75 5.25H15");
}

.sqgzs9b2w {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5");
}

</style>
