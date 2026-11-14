<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhxm3055v"/><path class="sz33em46t"/><path class="efted6usd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-fastener" /></template>
<style>
.bhxm3055v {
  d: path("m7.269 8.231l2.375-2.375a2.625 2.625 0 0 1 3.712 0l2.375 2.375a2.63 2.63 0 0 1 .769 1.856v8.788a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 6.5 18.875v-8.788a2.63 2.63 0 0 1 .769-1.856");
}

.efted6usd {
  d: path("M12.5 7.75c2-2.25 4-3.5 6.5-3.5m0-1.75V6M9 13.5h5M9 17h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sz33em46t {
  d: path("M10.25 8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
