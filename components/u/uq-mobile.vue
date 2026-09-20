<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="p1ir-y5hh"/><path class="iyix-mrpn"/><circle class="wtofxac3x"/><path class="y_h3pkn9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uq-mobile" /></template>
<style>
.iyix-mrpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.036 12.702v9.091c0 2.487 1.987 4.504 4.437 4.504s4.437-2.016 4.437-4.504v-9.091m8.62 0za4.44 4.44 0 0 1 4.437 4.447v4.7a4.44 4.44 0 0 1-4.437 4.447a4.44 4.44 0 0 1-4.438-4.447v-4.7a4.44 4.44 0 0 1 4.438-4.447m0 11.141l2.985 4.56M11.5 32.68a1.587 1.587 0 1 1 3.175 0v2.618M11.5 31.092v4.206m3.175-2.618a1.587 1.587 0 1 1 3.175 0v2.618");
}

.p1ir-y5hh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 27.64a66.6 66.6 0 0 1 29 0");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.wtofxac3x {
  cx: 29.307px;
  cy: 29.147px;
  r: 0.75px;
  fill: currentColor;
}

.y_h3pkn9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.307 31.092v4.206m1.663-6.349v5.556c0 .438.355.793.793.793H32m4.292-.801a1.587 1.587 0 0 1-2.966-.786v-1.032a1.587 1.587 0 0 1 3.175 0v.516h-3.176m-8.833-.515a1.587 1.587 0 1 1 3.175 0v1.03a1.587 1.587 0 1 1-3.175 0m0 1.588v-6.349m-4.876 3.731a1.587 1.587 0 0 1 3.175 0v1.03a1.587 1.587 0 0 1-3.175 0z");
}

</style>
