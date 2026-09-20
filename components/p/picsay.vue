<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ho5lrtbeq"/><path class="hwwih-nbg"/><g class="y9tr6bcfx"><path class="e6zujs6ns"/><path class="prwtusguo"/></g><path class="i76yjl5pa"/><circle class="tbyezm8ml"/><path class="pqh88mbtf"/><path class="rnyvdg_sn"/><path class="wxfgf3rrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:picsay" /></template>
<style>
.e6zujs6ns {
  d: path("M37.756 20.877v2.526a1.87 1.87 0 0 1-1.87 1.87c-.517 0-.985-.209-1.323-.547");
}

.ho5lrtbeq {
  width: 5.448px;
  height: 8.224px;
  x: 35.624px;
  y: 31.763px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.hwwih-nbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.655 39.986v-8.223h2.692c1.522 0 2.756 1.236 2.756 2.762s-1.234 2.761-2.756 2.761h-2.692m2.692 0l2.692 2.698m-12.353.002v-8.223h2.692c1.522 0 2.756 1.236 2.756 2.762s-1.234 2.761-2.756 2.761h-2.692");
}

.i76yjl5pa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.392 20.69a1.87 1.87 0 1 1-3.742 0v-1.216a1.87 1.87 0 1 1 3.742 0m0 3.087v-4.958m-9.848 4.138c.458.597 1.034.82 1.834.82h1.108a1.867 1.867 0 0 0 1.867-1.867v-.008a1.867 1.867 0 0 0-1.867-1.867h-1.222a1.87 1.87 0 0 1-1.869-1.869c0-1.034.839-1.873 1.873-1.873h1.102c.8 0 1.376.223 1.835.82m-5.998 5.722a1.87 1.87 0 0 1-3.495-.929v-1.216a1.87 1.87 0 0 1 3.494-.932");
}

.pqh88mbtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.086 17.603v4.958m-6.475 0v-7.484h2.45c1.385 0 2.508 1.126 2.508 2.514s-1.123 2.513-2.508 2.513h-2.45");
}

.prwtusguo {
  d: path("M37.756 17.79v3.087a1.87 1.87 0 1 1-3.742 0V17.79");
}

.rnyvdg_sn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.253 28.893c-4.403-1.492-9.341-5.279-9.586-9.875c-.33-6.198 8.21-11.238 18.338-11.238s18.337 5.031 18.337 11.238c-.43 8.66-10.92 11.403-18.81 11.234l-.471-.011");
}

.tbyezm8ml {
  cx: 16.086px;
  cy: 15.311px;
  r: 0.75px;
  fill: currentColor;
}

.wxfgf3rrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.253 28.893L14.04 40.22l9.021-9.98");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
