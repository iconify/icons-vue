<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="t1r1wbend"/><path clip-rule="evenodd" class="yyat1uody"/><path clip-rule="evenodd" class="h_u0bmjha"/><path clip-rule="evenodd" class="z0475pxta"/><path clip-rule="evenodd" class="d49m44arp"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:people-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d49m44arp {
  fill-rule: evenodd;
  d: path("M13 14a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.h_u0bmjha {
  fill-rule: evenodd;
  d: path("M18.95 14a1.5 1.5 0 0 1 1.5 1.5V17a1 1 0 1 0 2 0v-1.5a3.5 3.5 0 0 0-7 0V17a1 1 0 1 0 2 0v-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.t1r1wbend {
  fill-rule: evenodd;
  d: path("M7 11.25a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.yyat1uody {
  fill-rule: evenodd;
  d: path("M7.05 14a1.5 1.5 0 0 0-1.5 1.5V17a1 1 0 0 1-2 0v-1.5a3.5 3.5 0 0 1 7 0V17a1 1 0 1 1-2 0v-1.5a1.5 1.5 0 0 0-1.5-1.5M19 11.25a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0 2a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

.z0475pxta {
  fill-rule: evenodd;
  d: path("M13.05 16.75a2.5 2.5 0 0 0-2.5 2.5v1.5a1 1 0 0 1-2 0v-1.5a4.5 4.5 0 0 1 9 0v1.5a1 1 0 1 1-2 0v-1.5a2.5 2.5 0 0 0-2.5-2.5");
}

</style>
