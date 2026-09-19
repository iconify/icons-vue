<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="nep5nrbam"/><path class="m2i31bbje"/><path class="ju91glbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:securid" /></template>
<style>
.ju91glbwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.109 23.567l-6.929 6.928l-2.933-2.934");
}

.m2i31bbje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.44 20.45a8.723 8.723 0 0 0-16.68-2.882a6.66 6.66 0 0 0-2.998-.734a6.73 6.73 0 0 0-6.586 5.341a6.73 6.73 0 0 0 .058 13.461h24.583");
}

.nep5nrbam {
  cx: 35.817px;
  cy: 27.952px;
  r: 7.683px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
