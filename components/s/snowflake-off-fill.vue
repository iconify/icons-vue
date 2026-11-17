<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx8nctbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snowflake-off-fill" /></template>
<style>
.bx8nctbyw {
  fill: currentColor;
  d: path("M11 3a1 1 0 0 1 2 0v2.086l.293-.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414l.293.293Zm-8.293.293l18 18a.999.999 0 1 1-1.414 1.414l-4.297-4.297a1.001 1.001 0 0 1-1.703.797L13 18.914V21a1 1 0 0 1-2 0v-2.086l-.293.293a.999.999 0 1 1-1.414-1.414L11 16.086v-1.672l-.432-.432l-1.606.927l-.625 2.332a1 1 0 0 1-1.932-.518l.107-.4l-1.806 1.043a1 1 0 0 1-1-1.732l1.806-1.043l-.4-.107a1 1 0 0 1 .518-1.932l2.332.625l1.141-.659l-1.577-1.578l-1.896.508a1 1 0 0 1-.518-1.932l.4-.107l-1.806-1.043a.998.998 0 0 1-.265-1.511L1.293 4.707a.999.999 0 1 1 1.414-1.414m12.956 3.466a1 1 0 0 1 1.932.518l-.107.4l1.806-1.043a1 1 0 0 1 1 1.732l-1.806 1.043l.4.107a1 1 0 0 1-.518 1.932l-2.332-.625l-1.002.579a1 1 0 0 1-1-1.732l1.002-.579Z");
}

</style>
