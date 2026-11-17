<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k5dffabxz"/><path class="d77hv7bhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-duotone" /></template>
<style>
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

.k5dffabxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m20 13l-.034.034q.01-.01.004-.022a.02.02 0 0 0-.018-.012H15a2 2 0 0 0-2 1.999v4.953a.02.02 0 0 0 .012.018q.013.006.022-.004L13 20H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2Z");
}

</style>
