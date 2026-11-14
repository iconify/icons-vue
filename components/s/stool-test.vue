<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n4z0mdbod"/><path class="zzgg51bqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stool-test" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4z0mdbod {
  d: path("M9.375 9.5h5.25A4.375 4.375 0 0 1 19 13.875v3.25a4.375 4.375 0 0 1-4.375 4.375h-5.25A4.375 4.375 0 0 1 5 17.125v-3.25A4.375 4.375 0 0 1 9.375 9.5m-3.125-5h11.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75H6.25A1.75 1.75 0 0 1 4.5 7.75v-1.5A1.75 1.75 0 0 1 6.25 4.5M8 4.5v5m4-5v5m4-5v5m-4 0V15");
}

.zzgg51bqa {
  d: path("M10.5 17a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0");
}

</style>
