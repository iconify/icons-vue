<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwk7_cczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:omega-duotone" /></template>
<style>
.hwk7_cczk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 21L5.8579 21C6.7488 21 7.1949 19.9229 6.565 19.2929L5.636 18.364C3.9482 16.6761 3 14.3869 3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12C21 14.3869 20.0518 16.6761 18.364 18.364L17.435 19.2929C16.8051 19.9229 17.2512 21 18.1421 21L22 21");
}

</style>
