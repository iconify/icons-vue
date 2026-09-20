<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="aewi-8bnk"/><path clip-rule="evenodd" class="t1q3x1bzd"/><path clip-rule="evenodd" class="yhfl_4b0g"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:raise-hand-circle-off" /></template>
<style>
.aewi-8bnk {
  fill-rule: evenodd;
  d: path("M14.5 9a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M10 11.5a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.t1q3x1bzd {
  fill-rule: evenodd;
  d: path("M5 7a2.5 2.5 0 0 1 5 0v3.272c0 .883.31 1.737.874 2.415l1.394 1.673a1 1 0 1 1-1.536 1.28l-1.394-1.673A5.77 5.77 0 0 1 8 10.272V7a.5.5 0 0 0-1 0v3.75a4 4 0 0 0 .47 1.882l3.412 6.397a1 1 0 0 1-1.764.942l-3.412-6.398A6 6 0 0 1 5 10.75z");
}

.yhfl_4b0g {
  fill-rule: evenodd;
  d: path("M10.5 15a1 1 0 0 1 1-1H14a6 6 0 0 1 6 6v2a1 1 0 1 1-2 0v-2a4 4 0 0 0-4-4h-2.5a1 1 0 0 1-1-1m-.5 3.5a1 1 0 0 1 1 1V22a1 1 0 1 1-2 0v-2.5a1 1 0 0 1 1-1");
}

</style>
