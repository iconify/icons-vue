<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws7xjbhw"/><path class="xqze3wb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:var-review" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vws7xjbhw {
  d: path("M6 7h12a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-6.5A3.5 3.5 0 0 1 6 7m2.5-4.25L12 7l3.5-4.25");
}

.xqze3wb6c {
  d: path("m12.069 11.513l1.504.981a1.5 1.5 0 0 1 0 2.512l-1.504.981a1.5 1.5 0 0 1-2.319-1.256v-1.962a1.5 1.5 0 0 1 2.319-1.256");
}

</style>
