<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4rrz9b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:variable-duotone" /></template>
<style>
.n4rrz9b1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5C3 9 3 15 7 19M17 5c4 4 4 10 0 14M9 9l6 6m0-6l-6 6");
}

</style>
