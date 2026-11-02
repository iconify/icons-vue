<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6wun_gxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle-duocolor-sharp" /></template>
<style>
.g6wun_gxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 7h5v5a2.236 2.236 0 1 0 0 4v5H7v-5a2.236 2.236 0 1 1 0-4V7h5a2.236 2.236 0 1 1 4 0");
}

</style>
