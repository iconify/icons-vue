<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4x4alvwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-side-bulk-sharp" /></template>
<style>
.l4x4alvwl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 4c.351 0 .677.184.857.486L8.566 9H21a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5.586l-4.707 4.707A1 1 0 0 1 10 20H8a1 1 0 0 1-.928-1.371L8.523 15H5a1 1 0 0 1-.976-.783l-2-9A1 1 0 0 1 3 4Z");
}

</style>
