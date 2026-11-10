<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poeev55zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-ccw-square" /></template>
<style>
.poeev55zb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.4 2L12 4.25L14.4 6.5M12 4.25H18.4C19.2836 4.25 20 4.92 20 5.75V9M15 20V13C15 11.9 14.1046 11 13 11H6C4.8954 11 4 11.9 4 13V20C4 21.1 4.8954 22 6 22H13C14.1046 22 15 21.1 15 20Z");
}

</style>
