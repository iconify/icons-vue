<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft4kbctzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trophy-sharp" /></template>
<style>
.ft4kbctzl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 2L18 2L18 9C18 12.3137 15.3137 15 12 15C8.6863 15 6 12.3137 6 9L6 2ZM6 5L2 5L2 11L6.3249 11M18 5L22 5L22 11L17.6751 11M12 15L12 19M6 19L18 19L18 22L6 22L6 19Z");
}

</style>
