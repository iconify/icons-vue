<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evjlqiv3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-subtract-sharp" /></template>
<style>
.evjlqiv3q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L15 3L15 9L9 9L9 15L3 15ZM18 9L21 9L21 13.5M21 16.5L21 21L16.5 21M13.5 21L9 21L9 18");
}

</style>
