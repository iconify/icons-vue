<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-avucb6z"/><rect class="s2bi81bby"/><path class="kz77_obts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vmall" /></template>
<style>
.g-avucb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.509 24.015v6.599h3.3m2.144-6.599v6.599h3.3m-10.881 0l-2.145-6.599L24 30.614m.742-2.227h2.888m-12.37 2.227v-6.599l3.299 6.599l3.3-6.599v6.599m-8.745-6.599l-2.144 6.599l-2.228-6.599");
}

.kz77_obts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.123 17.588V13.22a2.255 2.255 0 0 1 2.26-2.26h12.81a2.256 2.256 0 0 1 2.26 2.26v4.368");
}

.s2bi81bby {
  width: 39px;
  height: 19.452px;
  x: 4.5px;
  y: 17.588px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.669px;
}

</style>
