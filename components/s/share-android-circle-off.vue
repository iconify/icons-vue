<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a-ivbfzwn"/><path class="mkgxjnerh"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:share-android-circle-off" /></template>
<style>
.a-ivbfzwn {
  fill-rule: evenodd;
  d: path("M8 16a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0-4a1 1 0 1 1 0 2a1 1 0 0 1 0-2m9-1a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0-4a1 1 0 1 1 0 2a1 1 0 0 1 0-2m0 14a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0-4a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.mkgxjnerh {
  d: path("m9.236 12.777l-.763-1.291l6.791-4.013l.763 1.291zm6.021 5.752l.772-1.286l-6.286-3.772l-.772 1.286z");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
