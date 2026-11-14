<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a69-1fdcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-percent" /></template>
<style>
.a69-1fdcl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.282 12.121l8.839-8.839a1.25 1.25 0 0 1 1.768 0l2.829 2.829a1.25 1.25 0 0 1 0 1.768l-8.839 8.839a1.25 1.25 0 0 1-1.768 0l-2.829-2.829a1.25 1.25 0 0 1 0-1.768Zm4.42-4.419l4.596 4.596m2.452 8.952l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
