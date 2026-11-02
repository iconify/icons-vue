<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ck4-m_2it"/><path class="n-87t3bgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telescope-duotone" /></template>
<style>
.ck4-m_2it {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.553 3.106a3.234 3.234 0 0 1 4.341 1.447a3.234 3.234 0 0 1-1.447 4.341l-10 5a3.236 3.236 0 1 1-2.894-5.788Z");
}

.ft5dv1b6b {
  fill: none;
}

.n-87t3bgg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m10 7l6-3a2.236 2.236 0 0 1 2 4L8 13a2.236 2.236 0 0 1-2-4zm4-2l2 4m-4 2L7 21m5-10l5 10");
}

</style>
