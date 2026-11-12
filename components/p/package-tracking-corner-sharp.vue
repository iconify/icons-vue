<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u23r6yvij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-tracking-corner-sharp" /></template>
<style>
.u23r6yvij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v12h4M4 8l2-4h12l2 4M4 8h16m-3 8h.01M17 21c-2-2-4-4-4-5a4 4 0 1 1 8 0c0 1-2 3-4 5");
}

</style>
