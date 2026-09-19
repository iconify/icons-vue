<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nal3wnpqr"/><path class="ee2iehb8t"/><path class="jlv3px45k"/><path class="dmqrnoton"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trilium-sender" /></template>
<style>
.dmqrnoton {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 23.523c-1.9 2.722-2.49 8.974.156 12.515");
}

.ee2iehb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 22.493c1.773-3.804 5.009-8.307 12.398-11.062M21.858 22.493c1.12-2.796-.394-8.438-5.116-9.138s-9.619.962-12.242 4.853c3.28 1.224 4.94 4.986 10.843 6.4c2.667.64 5.64.069 6.515-2.115");
}

.jlv3px45k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.858 22.493c-2.624-2.827-6.53-5.626-10.756-5.684m12.655 6.714c2.866 0 5.036 3.427 4.44 8.69a47 47 0 0 0-.196 8.417s-9.09-1.313-9.856-7.696c-.74-6.18 1.636-9.411 5.612-9.411");
}

.nal3wnpqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 22.493c2.173 2.398 7.195 3.017 11.523-1.88c4.533-5.128 8.22-9.531 8.22-9.531S35.63 4.26 27.848 9.114s-5.597 11.717-4.091 13.379");
}

</style>
