<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="u2ak06bit"/><path class="fmplpc_pp"/><rect class="quderxbzw"/><rect class="t334e_7gj"/><path class="jdxuj_qdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soup-stock-tokyo" /></template>
<style>
.fmplpc_pp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.972 22.353v9.055m0-1.923l4.109-4.08m-2.796 2.782l2.54 2.534m-29.529.28c.44.29.963.407 1.604.407h1.34c1.248 0 2.26-1.011 2.26-2.264s-1.012-2.264-2.26-2.264h-1.479A2.26 2.26 0 0 1 8.5 24.618a2.266 2.266 0 0 1 2.266-2.265H12.1c.968 0 1.665.269 2.22.992m3.632.197v6.735c0 .625.507 1.132 1.132 1.132h.34m-2.661-6h2.377m13.568 4.859c-.39.681-1.124 1.14-2.17 1.14s-2.06-1.013-2.06-2.264v-1.471c0-1.25 1.014-2.264 2.059-2.264s1.778.457 2.169 1.136m-11.019 1.128a2.264 2.264 0 0 1 4.528 0v1.472a2.264 2.264 0 0 1-4.528 0zm4.285-17.375v3.735a2.264 2.264 0 0 0 4.528 0v-3.735m0 3.735v2.264M10.45 7.263q.155-.021.316-.021h1.333c.969 0 1.665.269 2.22.992M8.68 15.305c.555.723 1.25.992 2.22.992h1.34c1.248 0 2.26-1.011 2.26-2.264s-1.012-2.264-2.26-2.264h-1.479a2.26 2.26 0 0 1-2.012-1.23m25.223 3.494a2.264 2.264 0 0 0 4.528 0v-1.471a2.264 2.264 0 0 0-4.528 0m0-2.264v9.055m-16-6.791a2.264 2.264 0 0 1 4.528 0v1.472a2.264 2.264 0 0 1-4.528 0zM11.5 38.344h3.411m-1.706 5.148v-5.148m17.737 0l-1.705 2.574l-1.706-2.574m1.705 5.148v-2.574");
}

.jdxuj_qdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.616 38.352V43.5m0-1.793l2.768-3.338m0 5.131l-2.118-2.574");
}

.quderxbzw {
  width: 3.411px;
  height: 5.148px;
  x: 17.058px;
  y: 38.344px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.705px;
  ry: 1.705px;
}

.t334e_7gj {
  width: 3.411px;
  height: 5.148px;
  x: 33.089px;
  y: 38.344px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.705px;
  ry: 1.705px;
}

.u2ak06bit {
  width: 31px;
  height: 31px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8px;
  ry: 8px;
}

</style>
