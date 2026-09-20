<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h2io0rlxm"/><path clip-rule="evenodd" class="q17og6f4c"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:studio-backdrop-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h2io0rlxm {
  fill-rule: evenodd;
  d: path("M6 6a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 20 6v7a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 6 13zm2 .5v6h10v-6z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.q17og6f4c {
  fill-rule: evenodd;
  d: path("M4.75 5.5a1 1 0 0 1 1-1h14.5a1 1 0 1 1 0 2H5.75a1 1 0 0 1-1-1m1.97 14l1.26-6.304l-1.96-.392l-1.381 6.902a1.5 1.5 0 0 0 1.47 1.794H19.89a1.5 1.5 0 0 0 1.471-1.794l-1.38-6.902l-1.962.392L19.28 19.5z");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
