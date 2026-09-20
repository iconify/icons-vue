<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hbsvss-ay"/><path clip-rule="evenodd" class="g995o9b5f"/><path clip-rule="evenodd" class="mr4ojgrse"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:stopwatch-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g995o9b5f {
  fill-rule: evenodd;
  d: path("M2.793 3.793a1 1 0 0 1 1.414 0l1.5 1.5a1 1 0 0 1-1.414 1.414l-1.5-1.5a1 1 0 0 1 0-1.414m11.5 2.914a1 1 0 0 0 1.414 0l1.5-1.5a1 1 0 0 0-1.414-1.414l-1.5 1.5a1 1 0 0 0 0 1.414M13.28 8.375a1 1 0 0 1-.155 1.406l-2.5 2a1 1 0 0 1-1.25-1.562l2.5-2a1 1 0 0 1 1.406.156M9 4V2h2v2z");
}

.hbsvss-ay {
  fill-rule: evenodd;
  d: path("M10 5.5a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11M2.5 11a7.5 7.5 0 1 1 15 0a7.5 7.5 0 0 1-15 0");
}

.mr4ojgrse {
  fill-rule: evenodd;
  d: path("M7.5 2a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
