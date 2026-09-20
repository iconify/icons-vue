<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dkols7bau"/><path class="k9qin_n-k"/><circle class="p16wx4bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nothing-x" /></template>
<style>
.dkols7bau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.155 28.832L19.168 7.845A8.007 8.007 0 1 0 7.845 19.168l20.987 20.987a8.007 8.007 0 1 0 11.323-11.323");
}

.k9qin_n-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.323 24l4.832-4.832A8.007 8.007 0 1 0 28.832 7.845l-4.847 4.847M12.677 24l-4.832 4.832a8.007 8.007 0 1 0 11.323 11.323l4.817-4.817");
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
