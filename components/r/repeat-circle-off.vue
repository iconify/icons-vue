<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nhih0mkbm"/><path clip-rule="evenodd" class="brt47ekkz"/><path clip-rule="evenodd" class="ewngvybtb"/><path clip-rule="evenodd" class="j5od2nblw"/><path clip-rule="evenodd" class="udl4or7nb"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:repeat-circle-off" /></template>
<style>
.brt47ekkz {
  fill-rule: evenodd;
  d: path("M19.983 7.727a.75.75 0 0 0-1.052.14l-1.546 2.017a.75.75 0 1 0 1.19.912l1.547-2.017a.75.75 0 0 0-.14-1.052");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ewngvybtb {
  fill-rule: evenodd;
  d: path("M5.48 12.323a5 5 0 0 1 5-5h7.86a1 1 0 1 1 0 2h-7.86a3 3 0 0 0-3 3v1a1 1 0 1 1-2 0zm3.008 7.928a.75.75 0 0 1-1.053-.13L5.89 18.14a.75.75 0 1 1 1.182-.923L8.619 19.2a.75.75 0 0 1-.13 1.052");
}

.j5od2nblw {
  fill-rule: evenodd;
  d: path("M6.024 18.273a.75.75 0 0 0 1.051-.14l1.547-2.017a.75.75 0 0 0-1.19-.912L5.884 17.22a.75.75 0 0 0 .139 1.052");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.nhih0mkbm {
  fill-rule: evenodd;
  d: path("M17.519 5.749a.75.75 0 0 1 1.052.13l1.547 1.982a.75.75 0 1 1-1.183.923L17.39 6.8a.75.75 0 0 1 .13-1.052");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.udl4or7nb {
  fill-rule: evenodd;
  d: path("M20.527 13.677a5 5 0 0 1-5 5H7.666a1 1 0 1 1 0-2h7.86a3 3 0 0 0 3-3v-1a1 1 0 1 1 2 0z");
}

</style>
