<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qjt6aqblq"/><path class="uyx0_-bap"/><path clip-rule="evenodd" class="rky6_ypal"/><path class="bh8sxknmt"/><path clip-rule="evenodd" class="owa4l2cof"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:monitor-circle-off" /></template>
<style>
.bh8sxknmt {
  d: path("M8.5 22.5a1 1 0 1 1 0-2h9a1 1 0 1 1 0 2z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.owa4l2cof {
  fill-rule: evenodd;
  d: path("M22 15H4v-1h18z");
}

.qjt6aqblq {
  fill-rule: evenodd;
  d: path("M20.5 4h-15A2.5 2.5 0 0 0 3 6.5v10A2.5 2.5 0 0 0 5.5 19h15a2.5 2.5 0 0 0 2.5-2.5v-10A2.5 2.5 0 0 0 20.5 4M5 6.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 .5.5v10a.5.5 0 0 1-.5.5h-15a.5.5 0 0 1-.5-.5z");
}

.rky6_ypal {
  fill-rule: evenodd;
  d: path("M14.5 17.5h-3a1 1 0 0 0-1 1V21a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-2.5a1 1 0 0 0-1-1m-2.5 3V19h2v1.5z");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.uyx0_-bap {
  d: path("M13 16.75a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5");
}

</style>
