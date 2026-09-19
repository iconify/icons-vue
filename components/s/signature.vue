<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ermesb34n"/><path class="pqc17nb8m"/><path class="i_h9zbbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:signature" /></template>
<style>
.ermesb34n {
  cx: 23.762px;
  cy: 21.062px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.284px;
  ry: 6.182px;
}

.i_h9zbbsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.864 27.237h-1.2m.617 0a11.99 11.99 0 0 1 .557-12.577m13.442-1.24l3.876 1.46m-2.002-.73c3.322 5.492 2.065 11.52-.467 13.087h4.587m1.833-10.207l2.219 1.733m-1.228-.96c.752 3.488-.233 8.805-1.344 9.434h6.748v-.814M5.81 32.589l36.22-.03m-32.968 2.31l29.848-.15M5.262 23.74l3.917-.716");
}

.pqc17nb8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.55 27.237h1.03m-5.331 0H4.5a13.1 13.1 0 0 1 4.79-9.115c-.285 3.627-.284 6.08.754 9.115m.926-10.069a28.2 28.2 0 0 1 9.51-3.887");
}

</style>
