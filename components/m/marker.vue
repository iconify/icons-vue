<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i19jh0qdx"/><path class="y30z-1bei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:marker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i19jh0qdx {
  d: path("m15.36 7.58l1.77 1.77q1.06 1.06 0 2.12L9.7 18.89q-1.06 1.06-2.12 0l-1.77-1.76q-1.06-1.06 0-2.12l7.43-7.43q1.06-1.06 2.12 0");
}

.y30z-1bei {
  d: path("m15.43 7.65l1.63 1.63q.42.42.84 0l.93-.93q.42-.42.26-1l-.74-2.72q-.16-.58-.58-.16l-2.34 2.34q-.42.42 0 .84m-3.61 1.34l3.89 3.89");
}

</style>
