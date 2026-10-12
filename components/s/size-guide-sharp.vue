<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l_jrv_b5l"/><path class="ccc4ueptn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:size-guide-sharp" /></template>
<style>
.ccc4ueptn {
  d: path("M10 2.75a2 2.5 0 0 0 4 0M2.75 19.5h18.5m-18.5-1.75v3.5m18.5-3.5v3.5");
}

.l_jrv_b5l {
  d: path("M9.75 2.75H15l.67.35l4.91 2.55l.67.35l-.25.71l-1 2.83l-.25.71l-.7-.28l-1.1-.44l-.7-.28v6.5H6.75v-6.5l-.7.28l-1.1.44l-.7.28L4 9.54L3 6.71L2.75 6l.67-.35L8.33 3.1L9 2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
