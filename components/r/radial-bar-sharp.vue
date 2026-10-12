<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wguz1jb6r"/><path class="x3m23lb9h"/><path class="nbvfrd4kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radial-bar-sharp" /></template>
<style>
.nbvfrd4kv {
  d: path("M12 9.5h2.5V12");
}

.wguz1jb6r {
  d: path("M12 3.5A8.5 8.5 0 1 1 3.5 12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3m23lb9h {
  d: path("M12 6.5a5.5 5.5 0 1 1-4.76 8.25");
}

</style>
