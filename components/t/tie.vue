<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpg3edbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tie" /></template>
<style>
.lpg3edbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.35 2.75h3.3q.6 0 .41.57l-.47 1.36q-.19.57-.79.57h-1.6q-.6 0-.79-.57l-.47-1.36q-.19-.57.41-.57m1.15 5h1q1 0 1.22.98l1.81 8.04q.22.98-.51 1.66l-2.29 2.14q-.73.68-1.46 0l-2.29-2.14q-.73-.68-.51-1.66l1.81-8.04q.22-.98 1.22-.98m-1.25 5.75l3.25-1.75");
}

</style>
