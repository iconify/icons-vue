<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ng_9b8bqu"/><path class="hvzutu3cm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hvzutu3cm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H8a4 4 0 0 1-4-4v-6.528a4 4 0 0 1 2.211-3.578l2.944-1.472A4 4 0 0 1 10.945 5h2.11a4 4 0 0 1 1.79.422l2.944 1.472A4 4 0 0 1 20 10.472V17a4 4 0 0 1-4 4zm-4 0v-7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v7m-8-5h8");
}

.ng_9b8bqu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 21H8a4 4 0 0 1-4-4v-6.528c0-1.515.856-2.9 2.211-3.578l2.944-1.472A4 4 0 0 1 10.944 5h2.112c.621 0 1.233.145 1.789.422l2.944 1.472A4 4 0 0 1 20 10.472V17a4 4 0 0 1-4 4");
}

</style>
