<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv4bf2a2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:waves-2-sharp-fill" /></template>
<style>
.iv4bf2a2y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7241 17.7897L2 17.5C2.9123 16.5421 4.1772 16 5.5 16C6.8228 16 8.0877 16.5421 9 17.5C9.9123 18.4579 11.1772 19 12.5 19C13.8228 19 15.0877 18.4579 16 17.5C16.9123 16.5421 18.1772 16 19.5 16C20.4 16 21.3 16.25 22 16.7L22.4592 16.9952M2 13L2 12C2 8.134 5.134 5 9 5C7.8 6.2 7.4 8 8 9.6C8.7 11.4 10.5 12.5 12.5 12.5C13.8228 12.5 15.0877 11.9579 16 11C16.9123 10.0421 18.1772 9.5 19.5 9.5C20.4 9.5 21.3 9.75 22 10.2L22.4592 10.4952");
}

</style>
