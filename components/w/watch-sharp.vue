<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj2wvy54y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:watch-sharp" /></template>
<style>
.uj2wvy54y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6L18 6L18 18L6 18L6 6ZM8 6L8.5 2L15.5 2L16 6M8 18L8.5 22L15.5 22L16 18");
}

</style>
