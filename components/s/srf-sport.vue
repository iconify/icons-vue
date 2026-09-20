<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="h0krwjr3z"/><path class="n88vey3cv"/></g><g class="y9tr6bcfx"><rect class="whp04_-cq"/><path class="zq-o37bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:srf-sport" /></template>
<style>
.h0krwjr3z {
  d: path("M21.083 22.845V14.04h2.883c1.63 0 2.951 1.324 2.951 2.958s-1.321 2.957-2.951 2.957l2.883 2.89m-14.355-.965c.54.704 1.217.965 2.159.965h1.304a2.197 2.197 0 0 0 2.197-2.196v-.01a2.197 2.197 0 0 0-2.197-2.197h-1.438a2.2 2.2 0 0 1-2.2-2.2c0-1.216.987-2.203 2.204-2.203h1.297c.942 0 1.62.262 2.16.965m12.429 3.438h2.863m-2.863 4.403v-8.806h4.404");
}

.n88vey3cv {
  d: path("M8.5 9.908h31v17.069h-31z");
}

.whp04_-cq {
  width: 4px;
  height: 5.3px;
  x: 23.48px;
  y: 32.792px;
  rx: 2px;
  ry: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zq-o37bja {
  d: path("M29.629 34.792a2 2 0 0 1 2-2m-2 0v5.3m-17.581-.447c.365.307.759.447 1.644.447h.45c.73 0 1.321-.593 1.321-1.325s-.592-1.325-1.322-1.325h-.897c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.644.447m19.441-2.097v5.95a1 1 0 0 0 1 1h.3m-2.35-5.3h2.1m-18.382 3.3a2 2 0 1 0 4 0v-1.3a2 2 0 1 0-4 0m0-2v8");
}

</style>
