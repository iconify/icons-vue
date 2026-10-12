<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6pcydgiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:observation-tower" /></template>
<style>
.o6pcydgiq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.6 5.5h8.8q.6 0 1.14.25l2.17 1q.54.25-.04.42l-3.09.91q-.58.17-1.18.17H8.6q-.6 0-1.18-.17l-3.09-.91q-.58-.17-.04-.42l2.17-1Q7 5.5 7.6 5.5m1.9 2.75c1 4.25 1 8.25-2.5 13m7.5-13c-1 4.25-1 8.25 2.5 13M12 5.5V2.75");
}

</style>
