<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jfp2fyuan"/><path class="jq_sb1b-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-fill" /></template>
<style>
.jfp2fyuan {
  fill: currentColor;
  d: path("M6 3H9V21H6C4.34315 21 3 19.65685 3 18V6C3 4.34315 4.34315 3 6 3Z");
  stroke: none;
}

.jq_sb1b-j {
  d: path("M6 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3ZM9 3V21M16 9L13 12L16 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
