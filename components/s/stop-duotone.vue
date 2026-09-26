<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8jto1bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stop-duotone" /></template>
<style>
.s8jto1bwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7C5 5.895431 5.895431 5 7 5L17 5C18.104569 5 19 5.895431 19 7L19 17C19 18.104569 18.104569 19 17 19L7 19C5.895431 19 5 18.104569 5 17Z");
}

</style>
