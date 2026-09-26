<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6kk9dbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture" /></template>
<style>
.t6kk9dbkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 8V7C22 5.34315 20.65685 4 19 4H5C3.34315 4 2 5.34315 2 7V17C2 18.65685 3.34315 20 5 20H8M14 12L20 12C21.10457 12 22 12.89543 22 14L22 18C22 19.10457 21.10457 20 20 20L14 20C12.89543 20 12 19.10457 12 18L12 14C12 12.89543 12.89543 12 14 12Z");
}

</style>
