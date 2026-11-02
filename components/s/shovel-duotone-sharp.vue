<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qtqd8wbkh"/><path class="webawkber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qtqd8wbkh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8.707 9.293l6 6a1 1 0 0 1 0 1.414l-2 2A1 1 0 0 1 12 19H6a1 1 0 0 1-1-1v-6c0-.265.105-.52.293-.707l2-2a1 1 0 0 1 1.414 0");
}

.webawkber {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 10l6 6l-2 2H6v-6zm3 3l6-6m-2-2l4 4");
}

</style>
