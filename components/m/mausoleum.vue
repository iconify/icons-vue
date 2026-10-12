<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcxee_2pk"/><path class="us6_uk24e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mausoleum" /></template>
<style>
.hcxee_2pk {
  d: path("M7.5 9.75a4.5 4.5 0 0 1 9 0Zm4.5-4.5v-2.5m-9.25 18v-1.5q0-.5.5-.5H4q.5 0 .5-.5v-.75q0-.5.5-.5t.5-.5v-6.25q0-.5.5-.5h12q.5 0 .5.5v6.25q0 .5.5.5t.5.5v.75q0 .5.5.5h.75q.5 0 .5.5v1.5q0 .5-.5.5H3.25q-.5 0-.5-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us6_uk24e {
  d: path("M10 17v-2.75a2 2 0 0 1 4 0V17");
}

</style>
