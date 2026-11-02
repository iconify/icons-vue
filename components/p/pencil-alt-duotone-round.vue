<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x8q-0mfjm"/><path class="exu65ub7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-duotone-round" /></template>
<style>
.exu65ub7n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16L14 6a2.828 2.828 0 1 1 4 4L8 20m0 0H4v-4");
}

.ft5dv1b6b {
  fill: none;
}

.x8q-0mfjm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 16c0-.265.105-.52.293-.707l10-10a3.828 3.828 0 0 1 5.414 5.414l-10 10A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1Z");
}

</style>
