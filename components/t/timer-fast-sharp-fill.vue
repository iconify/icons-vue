<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="rkvjxzbxx"/><path class="aac842uvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-fast-sharp-fill" /></template>
<style>
.aac842uvo {
  d: path("M8 2L16 2M12 2L12 6M17.6569 8.3431L19.2929 6.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkvjxzbxx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5C16.9706 5 21 9.0294 21 14C21 18.9706 16.9706 23 12 23C8.186 23 4.7861 20.5959 3.5147 17L8 17L8 15L3.0557 15C3.0186 14.668 3 14.3341 3 14C3 13.6659 3.0186 13.332 3.0557 13L9 13L9 11L3.5147 11C4.7861 7.4041 8.186 5 12 5ZM11 9L11 15L13 15L13 9L11 9Z");
  stroke: none;
}

</style>
