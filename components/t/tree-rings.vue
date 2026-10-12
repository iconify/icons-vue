<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pggej20es"/><path class="b8e-6zb0w"/><path class="shtca1b1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-rings" /></template>
<style>
.b8e-6zb0w {
  d: path("M6 12.5a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pggej20es {
  d: path("m12.95 3.07l.81.28q.94.33 1.86.73l1 .43q.92.4.61 1.35l-.14.42q-.32.95.63.63l.42-.14q.95-.31 1.49.53l.63 1q.54.84.52 1.84l-.01.86q-.02 1 0 2l.01.86q.02 1-.58 1.8l-.52.68q-.6.8-1.18 1.62l-.49.7q-.57.82-1.53 1.12l-.82.25q-.96.29-1.9.62l-.81.28q-.95.32-1.9 0l-.81-.28q-.94-.33-1.9-.62l-.82-.25q-.96-.3-1.53-1.12l-.49-.7q-.58-.82-1.18-1.62l-.52-.68q-.6-.8-.58-1.8l.01-.86q.02-1 0-2l-.01-.86q-.02-1 .58-1.8l.52-.68q.6-.8 1.18-1.62l.49-.7q.57-.82 1.53-1.12l.82-.25q.96-.29 1.9-.62l.81-.28q.95-.32 1.9 0");
}

.shtca1b1b {
  d: path("M8.9 12.85a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
