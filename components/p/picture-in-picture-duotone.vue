<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9umplbbp"/><path class="d2w370kzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-duotone" /></template>
<style>
.d2w370kzd {
  d: path("M22 8L22 7C22 5.3431 20.6569 4 19 4L5 4C3.3432 4 2 5.3431 2 7L2 17C2 18.6569 3.3432 20 5 20L8 20");
}

.j9umplbbp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 11L20 11C21.65685 11 23 12.34315 23 14L23 18C23 19.65685 21.65685 21 20 21L14 21C12.34315 21 11 19.65685 11 18L11 14C11 12.34315 12.34315 11 14 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
