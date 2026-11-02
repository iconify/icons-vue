<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8r31rbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-round" /></template>
<style>
.e8r31rbgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3a3 3 0 0 1 0 6a3 3 0 0 0 3 3h12a3 3 0 0 0 3-3a3 3 0 0 1 0-6m-7-3v12");
}

</style>
