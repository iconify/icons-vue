<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snfu0jf9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wildflower-meadow" /></template>
<style>
.snfu0jf9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19.5v-12a2 2 0 0 1-2-2v-2l2 1.25l2-1.25v2a2 2 0 0 1-2 2m-5.5 12v-6a2 2 0 0 1-2-2v-2l2 1.25l2-1.25v2a2 2 0 0 1-2 2m11 6v-5a2 2 0 0 1-2-2v-2l2 1.25l2-1.25v2a2 2 0 0 1-2 2m-15 5h19");
}

</style>
