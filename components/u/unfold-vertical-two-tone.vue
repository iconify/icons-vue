<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y-8mvnbqz"/><path class="w611auboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unfold-vertical-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w611auboi {
  d: path("M12 8L12 2M9 5L12 2L15 5M12 16L12 22M9 19L12 22L15 19");
}

.y-8mvnbqz {
  stroke-opacity: 0.4;
  d: path("M5 12L19 12");
}

</style>
