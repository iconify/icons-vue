<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coena5bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-sharp" /></template>
<style>
.coena5bez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 4l10 3l3 6l-4 4l-6-3Zm13 9l3 3l-4 4l-3-3M4 4l4 4m3 3h.01");
}

</style>
