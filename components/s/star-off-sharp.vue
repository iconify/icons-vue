<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2w1m6bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-off-sharp" /></template>
<style>
.p2w1m6bhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.42 4.27l1.72 4.14l.42 1.02l1.09.09l4.48.35l1.1.08l-.84.72l-3.42 2.91l-.83.71l.25 1.07l1.05 4.37l.26 1.07l-.94-.58l-3.82-2.34l-.94-.58l-.94.58l-3.82 2.34l-.94.58l.26-1.07l1.05-4.37l.25-1.07l-.83-.71l-3.42-2.91l-.84-.72l1.1-.08l4.48-.35l1.09-.09l.42-1.02l1.72-4.14l.42-1.02z");
}

</style>
