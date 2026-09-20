<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wksm57pxf"/><path class="z7kmi1b2u"/><path clip-rule="evenodd" class="ycaek2-lv"/><path clip-rule="evenodd" class="ftltivdtr"/><path clip-rule="evenodd" class="xjpf9jgmp"/><path clip-rule="evenodd" class="n_8q8hbgx"/><path clip-rule="evenodd" class="s23uwubwv"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:qr-code-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ftltivdtr {
  fill-rule: evenodd;
  d: path("M3 2a1 1 0 0 1 1 1v3.5a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1m0 16a1 1 0 0 1-1-1v-3.5a1 1 0 1 1 2 0V17a1 1 0 0 1-1 1");
}

.n_8q8hbgx {
  fill-rule: evenodd;
  d: path("M17 18a1 1 0 0 1-1-1v-3.5a1 1 0 1 1 2 0V17a1 1 0 0 1-1 1m0-16a1 1 0 0 1 1 1v3.5a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1");
}

.s23uwubwv {
  fill-rule: evenodd;
  d: path("M18 3a1 1 0 0 1-1 1h-3.5a1 1 0 1 1 0-2H17a1 1 0 0 1 1 1");
}

.wksm57pxf {
  fill-rule: evenodd;
  d: path("M6 6v2h2V6zM5 4.5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V5a.5.5 0 0 0-.5-.5zM12 6v2h2V6zm-1-1.5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V5a.5.5 0 0 0-.5-.5zM6 12v2h2v-2zm-1-1.5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-4a.5.5 0 0 0-.5-.5z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.xjpf9jgmp {
  fill-rule: evenodd;
  d: path("M2 17a1 1 0 0 1 1-1h3.5a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m16 0a1 1 0 0 1-1 1h-3.5a1 1 0 1 1 0-2H17a1 1 0 0 1 1 1");
}

.ycaek2-lv {
  fill-rule: evenodd;
  d: path("M2 3a1 1 0 0 1 1-1h3.5a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1");
}

.z7kmi1b2u {
  d: path("M10.5 11a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5z");
}

</style>
