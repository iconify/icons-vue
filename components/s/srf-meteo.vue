<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="h0krwjr3z"/><path class="n88vey3cv"/></g><g class="y9tr6bcfx"><rect class="mod1rccjg"/><path class="lgmnmosvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:srf-meteo" /></template>
<style>
.h0krwjr3z {
  d: path("M21.083 22.845V14.04h2.883c1.63 0 2.951 1.324 2.951 2.958s-1.321 2.957-2.951 2.957l2.883 2.89m-14.355-.965c.54.704 1.217.965 2.159.965h1.304a2.197 2.197 0 0 0 2.197-2.196v-.01a2.197 2.197 0 0 0-2.197-2.197h-1.438a2.2 2.2 0 0 1-2.2-2.2c0-1.216.987-2.203 2.204-2.203h1.297c.942 0 1.62.262 2.16.965m12.429 3.438h2.863m-2.863 4.403v-8.806h4.404");
}

.lgmnmosvn {
  d: path("M9.427 34.792a2 2 0 1 1 4 0v3.3m-4-5.3v5.3m4-3.3a2 2 0 1 1 4 0v3.3m8.798-6.95v5.95a1 1 0 0 0 1 1h.3m-2.35-5.3h2.1m-3.917 4.291a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4m12.843 1.64a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4");
}

.mod1rccjg {
  width: 4px;
  height: 5.3px;
  x: 34.574px;
  y: 32.792px;
  rx: 2px;
  ry: 2px;
}

.n88vey3cv {
  d: path("M8.5 9.908h31v17.069h-31z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
