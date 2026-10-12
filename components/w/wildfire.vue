<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zskrd6gin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wildfire" /></template>
<style>
.zskrd6gin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.56 3.27l3.38 5.71q.31.52-.29.52h-.55q-.6 0-.37.56l1.79 4.38q.23.56-.37.56h-7.8q-.6 0-.37-.56l1.79-4.38Q5 9.5 4.4 9.5h-.55q-.6 0-.29-.52l3.38-5.71q.31-.52.62 0M7.25 15v6.25m10.25 0a3.75 3.75 0 0 0 3.75-3.75c0-2.75-1.75-4.25-2.75-7.5c-.75 1.75-1.5 2.75-2.5 3.5c-.25-.75-.5-1-1-1.5c-.75 1.75-1.25 3-1.25 5.5a3.75 3.75 0 0 0 3.75 3.75");
}

</style>
