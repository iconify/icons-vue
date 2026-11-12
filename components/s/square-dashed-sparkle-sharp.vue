<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku2d5bb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-sparkle-sharp" /></template>
<style>
.ku2d5bb6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3H3v4m14-4h4v4M3 17v4h4m10 0h4v-4M11 3h2m-2 18h2M3 11v2m18-2v2m-9-5c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

</style>
