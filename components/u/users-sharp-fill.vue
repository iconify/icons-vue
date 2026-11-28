<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fpas2bcxi"/><path clip-rule="evenodd" class="bptmxumgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:users-sharp-fill" /></template>
<style>
.bptmxumgf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2C11.071 2 13 3.929 13 6C13 8.071 11.071 10 9 10C6.929 10 5 8.071 5 6C5 3.929 6.929 2 9 2ZM8 12H10C13.728 12 17 15.272 17 19V21C17 21.552 16.552 22 16 22H2C1.448 22 1 21.552 1 21V19C1 15.272 4.272 12 8 12Z");
  stroke: none;
}

.fpas2bcxi {
  d: path("M15 3H16C17.657 3 19 4.343 19 6C19 7.657 17.657 9 16 9H15M17.412 13.082L18.333 13.471C20.554 14.409 22 16.589 22 19V20C22 20.552 21.552 21 21 21H20");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
