<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex79rse2s"/><path class="s2ttqac1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-money" /></template>
<style>
.ex79rse2s {
  fill: currentColor;
  d: path("M10 10h1v4h-1zm6 0h1v4h-1zM4 18h16V6H4zm10-9c0-.55.45-1 1-1h3c.55 0 1 .45 1 1v6c0 .55-.45 1-1 1h-3c-.55 0-1-.45-1-1zM8 9c0-.55.45-1 1-1h3c.55 0 1 .45 1 1v6c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1zM5 8h2v8H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s2ttqac1o {
  fill: currentColor;
  d: path("M15 16h3c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1h-3c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1m1-6h1v4h-1zm-7 6h3c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1H9c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1m1-6h1v4h-1zM5 8h2v8H5zM2 4v16h20V4zm18 14H4V6h16z");
}

</style>
