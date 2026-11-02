<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i850hdcmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tooth-sharp" /></template>
<style>
.i850hdcmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4c-.8-.7-1.8-1-3-1a4 4 0 0 0-4 4c0 6 1 6 1 12a2 2 0 1 0 4 0v-1a2 2 0 1 1 4 0v1a2 2 0 1 0 4 0c0-6 1-6 1-12a4 4 0 0 0-4-4c-1.2 0-2.2.3-3 1");
}

</style>
