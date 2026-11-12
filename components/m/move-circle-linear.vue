<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c4v1z3pvf"/><path class="ua3-fnbfw"/><path class="gshkn9qqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-circle-linear" /></template>
<style>
.c4v1z3pvf {
  stroke-linejoin: round;
  d: path("M16.9497 14.1213L19.0711 12L16.9497 9.8787M19.0711 12H14.1213M7.05025 9.8787L4.92893 12L7.05025 14.1213M4.92893 12H9.87868");
}

.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ua3-fnbfw {
  stroke-linejoin: round;
  d: path("M9.87866 7.05025L12 4.92893L14.1213 7.05025M12 4.92893V9.87868M14.1213 16.9497L12 19.0711L9.87866 16.9497M12 19.0711V14.1213");
}

</style>
