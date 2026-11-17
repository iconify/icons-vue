<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stwiq5b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smoke-detector-fill-round" /></template>
<style>
.stwiq5b1r {
  fill: currentColor;
  d: path("M19 8h-1v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V8H5a3 3 0 1 1 0-6h14a3 3 0 1 1 0 6m-8.348 7.092c.299.411.473.898.473 1.408c0 1.089-.746 1.928-1.678 2.394c-.204.103-.572.338-.572.606s.368.503.572.606a1 1 0 1 1-.894 1.788c-.469-.234-.895-.559-1.205-.986a2.4 2.4 0 0 1-.473-1.408c0-1.089.746-1.928 1.678-2.394c.204-.103.572-.338.572-.606s-.368-.503-.572-.606a.999.999 0 1 1 .894-1.788c.469.234.895.559 1.205.986m6 0c.299.411.473.898.473 1.408c0 1.089-.746 1.928-1.678 2.394c-.204.103-.572.338-.572.606s.368.503.572.606a1 1 0 1 1-.894 1.788c-.469-.234-.895-.559-1.205-.986a2.4 2.4 0 0 1-.473-1.408c0-1.089.746-1.928 1.678-2.394c.204-.103.572-.338.572-.606s-.368-.503-.572-.606a1 1 0 1 1 .894-1.788c.469.234.895.559 1.205.986");
}

</style>
