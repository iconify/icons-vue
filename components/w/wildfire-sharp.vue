<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpk06abxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wildfire-sharp" /></template>
<style>
.lpk06abxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.56 3.27l3.38 5.71l.31.52H9.5l.23.56l1.79 4.38l.23.56h-9l.23-.56l1.79-4.38L5 9.5H3.25l.31-.52l3.38-5.71l.31-.52zM7.25 15v6.25m10.25 0a3.75 3.75 0 0 0 3.75-3.75c0-2.75-1.75-4.25-2.75-7.5l-1.026 2.395L16 13.5l-.25-.75L15 12c-.75 1.75-1.25 3-1.25 5.5a3.75 3.75 0 0 0 3.75 3.75Z");
}

</style>
