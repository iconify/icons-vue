<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pmyt1sces"/><path clip-rule="evenodd" class="x3sbacc9c"/><path clip-rule="evenodd" class="h2z1_db0y"/><path clip-rule="evenodd" class="ahaw7rbew"/><path clip-rule="evenodd" class="t7mctzbai"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:move-y-circle-off" /></template>
<style>
.ahaw7rbew {
  fill-rule: evenodd;
  d: path("M8.232 16.026a1 1 0 0 1 1.408-.128l4 3.334a1 1 0 1 1-1.28 1.536l-4-3.333a1 1 0 0 1-.128-1.408");
}

.cuyn6tgcc {
  fill: currentColor;
}

.h2z1_db0y {
  fill-rule: evenodd;
  d: path("M13 7a1 1 0 0 1 1 1v8a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1m4.768 9.026a1 1 0 0 1-.128 1.409l-4 3.333a1 1 0 0 1-1.28-1.536l4-3.334a1 1 0 0 1 1.408.128");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.pmyt1sces {
  fill-rule: evenodd;
  d: path("M8.232 9.974a1 1 0 0 1 .128-1.409l4-3.333a1 1 0 1 1 1.28 1.536l-4 3.334a1 1 0 0 1-1.408-.128");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.t7mctzbai {
  fill-rule: evenodd;
  d: path("M13 19a1 1 0 0 1-1-1v-8a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

.x3sbacc9c {
  fill-rule: evenodd;
  d: path("M17.768 9.974a1 1 0 0 1-1.408.128l-4-3.334a1 1 0 1 1 1.28-1.536l4 3.333a1 1 0 0 1 .128 1.409");
}

</style>
