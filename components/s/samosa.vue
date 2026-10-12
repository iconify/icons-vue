<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmow9zb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:samosa" /></template>
<style>
.vmow9zb1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.1q1-1.5 2.1-.1l8.8 13.6q.7 1.4-.9 1.8a1.6 1.6 0 0 1-3.2 0a1.6 1.6 0 0 1-3.2 0a1.6 1.6 0 0 1-3.2 0a1.6 1.6 0 0 1-3.2 0a1.6 1.6 0 0 1-3.2 0q-1.6 0-.9-1.4Zm1.5 3.15L7.75 17M12 9l2.25 3.5");
}

</style>
