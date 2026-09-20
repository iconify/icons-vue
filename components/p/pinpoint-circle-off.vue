<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="no1gr0bcd"/><path clip-rule="evenodd" class="lra91obnp"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:pinpoint-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.lra91obnp {
  fill-rule: evenodd;
  d: path("M5.5 11.123C5.5 15.366 9.882 22.5 13 22.5s7.5-7.134 7.5-11.377C20.5 6.917 17.146 3.5 13 3.5s-7.5 3.417-7.5 7.623m13 0c0 3.28-3.745 9.377-5.5 9.377s-5.5-6.097-5.5-9.377C7.5 8.013 9.967 5.5 13 5.5s5.5 2.513 5.5 5.623");
}

.no1gr0bcd {
  fill-rule: evenodd;
  d: path("M13 14.5a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0-5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
