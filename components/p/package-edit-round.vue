<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4a8pxxwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-round" /></template>
<style>
.k4a8pxxwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V8zM4 8h16M9 17v-2l4-4l2 2l-4 4Z");
}

</style>
