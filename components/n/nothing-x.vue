<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6vliab8r"/><path class="ibg0hre8r"/><circle class="p16wx4bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nothing-x" /></template>
<style>
.c6vliab8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.155 28.832L19.168 7.845a8.007 8.007 0 0 0-11.323 0h0a8.007 8.007 0 0 0 0 11.323l20.987 20.987a8.007 8.007 0 0 0 11.323 0h0a8.007 8.007 0 0 0 0-11.323");
}

.ibg0hre8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.323 24l4.832-4.832a8.007 8.007 0 0 0 0-11.323h0a8.007 8.007 0 0 0-11.323 0l-4.847 4.847M12.677 24l-4.832 4.832a8.007 8.007 0 0 0 0 11.323h0a8.007 8.007 0 0 0 11.323 0l4.817-4.817");
}

.p16wx4bbl {
  cx: 34.345px;
  cy: 34.494px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
