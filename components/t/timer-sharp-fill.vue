<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="fn5wc5b_w"/><path class="aac842uvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-sharp-fill" /></template>
<style>
.aac842uvo {
  d: path("M8 2L16 2M12 2L12 6M17.6569 8.3431L19.2929 6.7071");
}

.fn5wc5b_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5C16.9706 5 21 9.0294 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 9.0294 7.0294 5 12 5ZM11 9L11 15L13 15L13 9L11 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
