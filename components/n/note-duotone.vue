<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bvxqas0zh"/><path class="d77hv7bhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-duotone" /></template>
<style>
.bvxqas0zh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 20.707A1 1 0 0 1 13 21H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v7c0 .265-.105.52-.293.707ZM15 13a2 2 0 0 0-2 2v4l6-6Z");
}

.d77hv7bhl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v7m0 0l-7 7m0 0v-5a2 2 0 0 1 2-2h5");
}

.ft5dv1b6b {
  fill: none;
}

</style>
