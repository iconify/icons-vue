<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k50xs4sbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shift" /></template>
<style>
.k50xs4sbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19h-2a1 1 0 0 1-1-1v-4a1 1 0 0 0-1-1H5c-.369 0-.369-.631 0-1l6-6a1.414 1.414 0 0 1 2 0l6 6c.369.369.369 1 0 1h-3a1 1 0 0 0-1 1v4a1 1 0 0 1-1 1z");
}

</style>
