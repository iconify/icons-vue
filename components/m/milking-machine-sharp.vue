<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ed7dpyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:milking-machine-sharp" /></template>
<style>
.g-ed7dpyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3v5m3-5v5m3-5v5m3-5v5m-9.4 0h10.4l-.33.5l-1.34 2l-.33.5h-7l-.33-.5l-1.34-2l-.33-.5zm4.9 3v8.75h6.15m.6-7.25h6.25l-.09 1l-.57 6.75l-.09 1h-5.75l-.09-1l-.57-6.75l-.09-1zm-.8 2.5h6.85");
}

</style>
