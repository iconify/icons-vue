<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh8x739my"/><path class="q4cl8qbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-bar" /></template>
<style>
.nh8x739my {
  fill: currentColor;
  d: path("M9.23 9L12 12.11L14.77 9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q4cl8qbpl {
  fill: currentColor;
  d: path("M21 5V3H3v2l8 9v5H6v2h12v-2h-5v-5zM5.66 5h12.69l-1.78 2H7.43zM12 12.11L9.23 9h5.54z");
}

</style>
