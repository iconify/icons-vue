<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anyn4pxcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:padding-down-24-regular" /></template>
<style>
.anyn4pxcd {
  fill: currentColor;
  d: path("M4.5 2.75c0 .414.336.75.75.75h13a.75.75 0 0 0 0-1.5h-13a.75.75 0 0 0-.75.75m0 18.5c0 .414.336.75.75.75h.867a.75.75 0 0 0 0-1.5H5.25a.75.75 0 0 0-.75.75m3.467 0c0 .414.335.75.75.75h1.733a.75.75 0 0 0 0-1.5H8.717a.75.75 0 0 0-.75.75m4.333 0c0 .414.336.75.75.75h1.733a.75.75 0 0 0 0-1.5H13.05a.75.75 0 0 0-.75.75m4.333 0c0 .414.336.75.75.75h.867a.75.75 0 0 0 0-1.5h-.867a.75.75 0 0 0-.75.75m-4.353-2.47a.75.75 0 0 1-1.06 0l-5-5a.75.75 0 1 1 1.06-1.06L11 16.44V5.75a.75.75 0 0 1 1.5 0v10.69l3.72-3.72a.75.75 0 1 1 1.06 1.06z");
}

</style>
