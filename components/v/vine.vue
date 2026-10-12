<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggqyehqnp"/><path class="db3bvab_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vine" /></template>
<style>
.db3bvab_w {
  d: path("M12.25 13.75C13.5 12 16 11 18.5 11.5c-1 2.25-3.5 3.25-6.25 2.25m-3.5-6.5c-1.25-1.75-3.5-2.5-6-2c1 2.25 3.25 3 6 2m2 9.75c2.75 0 4.75 1.25 4.75 2.75c0 .9-.75 1.5-1.5 1.5s-1.25-.5-1.25-1.25");
}

.ggqyehqnp {
  d: path("M9 21.25c0-3 3.5-4 3.5-7s-4-4-4-7c0-2.25 1.75-4 4.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
