<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ycumi-5ma"/><path clip-rule="evenodd" class="mym9o3lhb"/><path class="p-oihopda"/><path clip-rule="evenodd" class="pzn77cc3b"/><path class="b9zb6ibet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:truck" /></template>
<style>
.b9zb6ibet {
  d: path("M3.29 10.1H5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5v-.85l.015-.122l.29-1.15a.5.5 0 0 1 .485-.378");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mym9o3lhb {
  fill-rule: evenodd;
  d: path("M18 4.5H8a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6.5a2 2 0 0 0-2-2M8 14V6.5h10V14z");
}

.p-oihopda {
  d: path("M10.25 8.75a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1zm0 2a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1zm0 2a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1z");
}

.pzn77cc3b {
  fill-rule: evenodd;
  d: path("M6 7.5H2.736a2 2 0 0 0-1.92 1.442L0 11.75V14a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V9.5a2 2 0 0 0-2-2M2 14v-1.966L2.736 9.5H6V14z");
}

.ycumi-5ma {
  d: path("M7.5 18.75a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5m9 0a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5");
}

</style>
