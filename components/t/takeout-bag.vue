<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd8yigbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:takeout-bag" /></template>
<style>
.zd8yigbji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.37 3.83l1.01-.66Q8 2.75 8.6 3.2l.8.6q.6.45 1.2 0l.8-.6q.6-.45 1.2 0l.8.6q.6.45 1.2 0l.8-.6q.6-.45 1.22-.03l1.01.66q.62.42.64 1.17l.46 15.5q.02.75-.73.75H6q-.75 0-.73-.75L5.73 5q.02-.75.64-1.17m-.72 3.92h12.7m-6.35 0v3");
}

</style>
