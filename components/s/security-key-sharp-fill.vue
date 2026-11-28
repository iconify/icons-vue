<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="b7eadertg"/><path class="g5m50qbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:security-key-sharp-fill" /></template>
<style>
.b7eadertg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 9L19 16C19 16.5523 18.5523 17 18 17L6 17C5.4477 17 5 16.5523 5 16L5 2C5 1.4477 5.4477 1 6 1L18 1C18.5523 1 19 1.4477 19 2ZM14.1213 11.1213C14.6631 10.5795 15 9.8282 15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C12.8282 12 13.5795 11.6631 14.1213 11.1213ZM12.7071 9.7071C12.8892 9.5251 13 9.2764 13 9C13 8.4477 12.5523 8 12 8C11.4477 8 11 8.4477 11 9C11 9.5523 11.4477 10 12 10C12.2764 10 12.5251 9.8892 12.7071 9.7071Z");
  stroke: none;
}

.g5m50qbhf {
  d: path("M9 16L9 22L15 22L15 16");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
