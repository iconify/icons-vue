<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kvd9w8nhr"/><path clip-rule="evenodd" class="bptmxumgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-plus-sharp-fill" /></template>
<style>
.bptmxumgf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2C11.071 2 13 3.929 13 6C13 8.071 11.071 10 9 10C6.929 10 5 8.071 5 6C5 3.929 6.929 2 9 2ZM8 12H10C13.728 12 17 15.272 17 19V21C17 21.552 16.552 22 16 22H2C1.448 22 1 21.552 1 21V19C1 15.272 4.272 12 8 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kvd9w8nhr {
  d: path("M19 2V10M15 6H23");
}

</style>
