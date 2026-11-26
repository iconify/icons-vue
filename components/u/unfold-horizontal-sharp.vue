<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra1wdrbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unfold-horizontal-sharp" /></template>
<style>
.ra1wdrbje {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12L2 12M5.2929 8.7071L2 12L5.2929 15.2929M15 12L22 12M18.7071 8.7071L22 12L18.7071 15.2929M12 4L12 20");
}

</style>
