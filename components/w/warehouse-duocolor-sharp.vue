<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wg4if2bmf"/><path class="eoblojbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-duocolor-sharp" /></template>
<style>
.eoblojbgg {
  d: path("M4 21V8l6-3h4l6 3v13z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wg4if2bmf {
  stroke-opacity: 0.4;
  d: path("M8 21v-9h8v9m-8-5h8");
}

</style>
