<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="py_z87bnd"/><path class="ab0twwb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-duotone-sharp" /></template>
<style>
.ab0twwb_u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17c-3.174.157-5.366-3.13-4-6c-.962-2.253.56-4.788 3-5c1.676-3.251 6.324-3.251 8 0c2.44.212 3.962 2.747 3 5c1.366 2.87-.826 6.157-4 6Zm3 4v-4m0 0v-3m-3-3l3 3l3-3");
}

.ft5dv1b6b {
  fill: none;
}

.py_z87bnd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 11a3.6 3.6 0 0 1 3-5a4.5 4.5 0 0 1 8 0a3.602 3.602 0 0 1 3 5a4.2 4.2 0 0 1-4 6H9a4.2 4.2 0 0 1-4-6");
}

</style>
