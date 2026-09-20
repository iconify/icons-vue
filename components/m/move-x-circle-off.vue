<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eiyziq5id"/><path clip-rule="evenodd" class="qe-xuib1g"/><path clip-rule="evenodd" class="w14f7pbgy"/><path clip-rule="evenodd" class="d2_qwybaa"/><path clip-rule="evenodd" class="g4w-3vbdg"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:move-x-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d2_qwybaa {
  fill-rule: evenodd;
  d: path("M9.974 8.232a1 1 0 0 1 .128 1.408l-3.334 4a1 1 0 1 1-1.536-1.28l3.333-4a1 1 0 0 1 1.409-.128");
}

.eiyziq5id {
  fill-rule: evenodd;
  d: path("M16.026 8.232a1 1 0 0 1 1.409.128l3.333 4a1 1 0 1 1-1.536 1.28l-3.334-4a1 1 0 0 1 .128-1.408");
}

.g4w-3vbdg {
  fill-rule: evenodd;
  d: path("M7 13a1 1 0 0 1 1-1h8a1 1 0 0 1 0 2H8a1 1 0 0 1-1-1");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.qe-xuib1g {
  fill-rule: evenodd;
  d: path("M16.026 17.768a1 1 0 0 1-.128-1.408l3.334-4a1 1 0 1 1 1.536 1.28l-3.333 4a1 1 0 0 1-1.408.128");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.w14f7pbgy {
  fill-rule: evenodd;
  d: path("M19 13a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m-9.026 4.768a1 1 0 0 1-1.409-.128l-3.333-4a1 1 0 1 1 1.536-1.28l3.334 4a1 1 0 0 1-.128 1.408");
}

</style>
