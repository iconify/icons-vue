<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="j7wc8qbcn"/><path clip-rule="evenodd" class="cl0n44_ub"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-camera-circle-off" /></template>
<style>
.cl0n44_ub {
  fill-rule: evenodd;
  d: path("M9.5 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j7wc8qbcn {
  fill-rule: evenodd;
  d: path("M8.696 8.078L8.398 9H7.5a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h11a3 3 0 0 0 3-3v-6a3 3 0 0 0-3-3h-.899l-.297-.922A3 3 0 0 0 14.449 6H11.55a3 3 0 0 0-2.855 2.078M7.5 11h2.354l.745-2.307A1 1 0 0 1 11.551 8h2.898a1 1 0 0 1 .951.693L16.145 11H18.5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
