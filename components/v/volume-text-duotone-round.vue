<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ee17ggbie"/><path class="xnpud1bub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-text-duotone-round" /></template>
<style>
.ee17ggbie {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.586 9l3.707-3.707c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v12c.001.203-.047.402-.14.582c-.371.712-1.242.835-1.932.549a2 2 0 0 1-.635-.424L15.586 15H14a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.xnpud1bub {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 10l4-4c.369-.369 1-.369 1 0v12c0 .369-.631.369-1 0l-4-4h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1zM3 9h6M6 9v6");
}

</style>
