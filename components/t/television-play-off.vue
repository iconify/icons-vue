<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="q6-7rfosz"/><path clip-rule="evenodd" class="fwf1ukb4o"/><path clip-rule="evenodd" class="g-aqh5b7p"/><path clip-rule="evenodd" class="flx4iwb3w"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:television-play-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.flx4iwb3w {
  fill-rule: evenodd;
  d: path("M12.5 11.5a.5.5 0 0 1-.238.426l-3.25 2a.5.5 0 0 1-.762-.426v-4a.5.5 0 0 1 .762-.426l3.25 2a.5.5 0 0 1 .238.426m-3.25-1.105v2.21l1.796-1.105z");
}

.fwf1ukb4o {
  fill-rule: evenodd;
  d: path("M9.875 5.78a1 1 0 0 1-.156-1.405l2-2.5a1 1 0 0 1 1.562 1.25l-2 2.5a1 1 0 0 1-1.406.156");
}

.g-aqh5b7p {
  fill-rule: evenodd;
  d: path("M10.125 5.78a1 1 0 0 0 .156-1.405l-2-2.5a1 1 0 1 0-1.562 1.25l2 2.5a1 1 0 0 0 1.406.156M12 11.5l-3.25 2v-4z");
}

.q6-7rfosz {
  fill-rule: evenodd;
  d: path("M4 8v7a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1m-2 7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H5a3 3 0 0 0-3 3z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
