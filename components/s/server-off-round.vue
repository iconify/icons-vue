<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5ec_vnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-round" /></template>
<style>
.bj5ec_vnd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H6a3 3 0 0 1-3-3c0-1.085.138-2.473 1-3m6 0h8a3 3 0 0 1 0 6h-2m4 10c-.455.278-1.428 0-2 0H6a3 3 0 0 1 0-6h8m-7 3h.01M2 2l20 20");
}

</style>
