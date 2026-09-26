<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh3iaab3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-off" /></template>
<style>
.zh3iaab3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.12132 20.12132C19.55871 20.68393 18.79565 21 18 21H6C4.34315 21 3 19.65685 3 18V6C3 5.20435 3.31607 4.44129 3.87868 3.87868M3 9H9M3 15H15M12 12V21M8.65685 3H18C19.65685 3 21 4.34315 21 6V15.34315M14.65685 9H21M2 2L22 22");
}

</style>
