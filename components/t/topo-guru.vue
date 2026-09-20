<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j02h3fbnj"/><path class="pmulwbc6u"/><path class="ldu8gs4fs"/><path class="or80d1mqd"/><path class="evqka4byz"/><path class="wd0bo7bqj"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:topo-guru" /></template>
<style>
.evqka4byz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.42 42.331s-4.672-11.83-4.977-13.967s-1.6-10.116-.167-15.851c.389-1.555 2.998-5.772 6.968-3.69s7.578 6.854 8.661 7.465s3.884 2.251 6.996-.86c.171-.172 4.104-6.202 6.135-8.4M30.059 42.455s2.186-6.313 5.39-8.163c3.824-2.208 6.26-.555 6.26-.555M5.51 18.55s3.43-1.1 4.137-1.14");
}

.j02h3fbnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.173 28.822s2.255-2.516 2.255-4.511c0-1.481-1.006-2.256-2.255-2.256s-2.256 1.007-2.256 2.256c0 1.995 2.256 4.51 2.256 4.51");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ldu8gs4fs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.469 14.128s2.255-2.516 2.255-4.511c0-1.477-1.006-2.255-2.255-2.255s-2.256 1.006-2.256 2.255c0 1.995 2.256 4.511 2.256 4.511");
}

.or80d1mqd {
  fill: currentColor;
  d: path("M30.469 10.367a.751.751 0 0 1 0-1.5a.751.751 0 0 1 0 1.5");
}

.pmulwbc6u {
  fill: currentColor;
  d: path("M38.173 25.06a.751.751 0 0 1 0-1.5a.751.751 0 0 1 0 1.5");
}

.wd0bo7bqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.137 17.315s6.829.278 6.829 5.136s-2.71 6.444-5.26 7.127c-2.55.684-8.629-.317-9.196-.496");
}

</style>
