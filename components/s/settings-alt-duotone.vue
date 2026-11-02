<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hk0pd_dsg"/><path class="vh9bdsb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hk0pd_dsg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m19.342 18.447l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236v7.528a3 3 0 0 1-1.658 2.683M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.vh9bdsb3e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 8.236v7.528a2 2 0 0 1-1.106 1.789l-6 3a2 2 0 0 1-1.788 0l-6-3A2 2 0 0 1 4 15.763V8.237a2 2 0 0 1 1.106-1.789l6-3a2 2 0 0 1 1.788 0l6 3A2 2 0 0 1 20 8.237M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
