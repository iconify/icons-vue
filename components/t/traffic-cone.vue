<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foe0ikw_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:traffic-cone" /></template>
<style>
.foe0ikw_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 22L9.5724 3.4253C9.8262 2.5793 10.6048 2 11.4881 2L12.5119 2C13.3952 2 14.1738 2.5793 14.4276 3.4253L20 22M2 22L22 22M8 8.6667L16 8.6667M6 15.3333L18 15.3333");
}

</style>
