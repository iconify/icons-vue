<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gax8di68h"/><path class="gjddl9vru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rotation-lock-sharp" /></template>
<style>
.gax8di68h {
  d: path("M16.25 4.64a8.5 8.5 0 1 1-8.5 0M4.93 3.61l2.82 1.03l-.52 2.95");
}

.gjddl9vru {
  d: path("M9 11.25h6v5H9zm1.25 0v-3h3.5v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
