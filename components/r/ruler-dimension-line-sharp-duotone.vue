<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq-284bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ruler-dimension-line-sharp-duotone" /></template>
<style>
.uq-284bjh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6L2 18M22 6L22 18M2 12L22 12M7 12L7 16M12 12L12 17M17 12L17 16");
}

</style>
