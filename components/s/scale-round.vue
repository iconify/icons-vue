<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj80a9b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scale-round" /></template>
<style>
.vj80a9b2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3v18m-4 0h8M6 6h12M6 6l3 7a3.25 3.25 0 0 1-6 0Zm12 0l3 7a3.25 3.25 0 0 1-6 0Z");
}

</style>
