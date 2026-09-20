<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kwzfm0bkz"/><path class="gbqb6oopz"/><path clip-rule="evenodd" class="sojxdkbvk"/><path clip-rule="evenodd" class="r7wxzgbat"/><path clip-rule="evenodd" class="y-fhtpb_f"/><path clip-rule="evenodd" class="rp5ibtben"/><path clip-rule="evenodd" class="lyg595b8g"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:qr-code-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gbqb6oopz {
  d: path("M13.5 14a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.kwzfm0bkz {
  fill-rule: evenodd;
  d: path("M9 9v2h2V9zM8 7.5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V8a.5.5 0 0 0-.5-.5zM15 9v2h2V9zm-1-1.5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V8a.5.5 0 0 0-.5-.5zM9 15v2h2v-2zm-1-1.5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-4a.5.5 0 0 0-.5-.5z");
}

.lyg595b8g {
  fill-rule: evenodd;
  d: path("M21 6a1 1 0 0 1-1 1h-3.5a1 1 0 1 1 0-2H20a1 1 0 0 1 1 1");
}

.r7wxzgbat {
  fill-rule: evenodd;
  d: path("M6 5a1 1 0 0 1 1 1v3.5a1 1 0 0 1-2 0V6a1 1 0 0 1 1-1m0 16a1 1 0 0 1-1-1v-3.5a1 1 0 1 1 2 0V20a1 1 0 0 1-1 1");
}

.rp5ibtben {
  fill-rule: evenodd;
  d: path("M20 21a1 1 0 0 1-1-1v-3.5a1 1 0 1 1 2 0V20a1 1 0 0 1-1 1m0-16a1 1 0 0 1 1 1v3.5a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1");
}

.sojxdkbvk {
  fill-rule: evenodd;
  d: path("M5 6a1 1 0 0 1 1-1h3.5a1 1 0 0 1 0 2H6a1 1 0 0 1-1-1");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.y-fhtpb_f {
  fill-rule: evenodd;
  d: path("M5 20a1 1 0 0 1 1-1h3.5a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1m16 0a1 1 0 0 1-1 1h-3.5a1 1 0 1 1 0-2H20a1 1 0 0 1 1 1");
}

</style>
