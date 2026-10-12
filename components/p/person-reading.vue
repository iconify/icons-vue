<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wijmr5spd"/><path class="yg4503prc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-reading" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

.yg4503prc {
  d: path("M12 13c-1.75-1.25-4-1.75-7.25-1.75v7.5c3.25 0 5.5.5 7.25 1.75c1.75-1.25 4-1.75 7.25-1.75v-7.5c-3.25 0-5.5.5-7.25 1.75m0 .25v6.5");
}

</style>
