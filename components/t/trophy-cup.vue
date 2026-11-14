<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1t9pbnwp"/><path class="i8hjvsbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy-cup" /></template>
<style>
.i8hjvsbpo {
  d: path("M7 5H4v2a3 3 0 0 0 3.25 3M17 5h3v2a3 3 0 0 1-3.25 3M12 13.5v4m-4 0h8V21H8Z");
}

.k1t9pbnwp {
  d: path("M7 3h10v5.5a5 5 0 0 1-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
