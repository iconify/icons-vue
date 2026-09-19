<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8sx146mv"/><path class="vevarq4mu"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:player" /></template>
<style>
.f8sx146mv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.302 24.648v2.694a1.995 1.995 0 0 1-1.995 1.995h0c-.551 0-1.05-.223-1.41-.584");
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

.vevarq4mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.302 21.356v3.292a1.995 1.995 0 0 1-1.995 1.996h0a1.995 1.995 0 0 1-1.995-1.996v-3.292m12.193 1.996c0-1.102.893-1.996 1.995-1.996h0m-1.995 0v5.288m-20.981-7.981v6.983c0 .551.447.998.998.998h.299m5.379-1.996a1.995 1.995 0 0 1-1.995 1.996h0a1.995 1.995 0 0 1-1.995-1.996v-1.297c0-1.101.893-1.995 1.995-1.995h0c1.102 0 1.995.894 1.995 1.995m0 3.293v-5.288m11.953 4.281a2 2 0 0 1-1.734 1.007h0a1.995 1.995 0 0 1-1.995-1.995v-1.297c0-1.102.893-1.996 1.995-1.996h0c1.102 0 1.996.894 1.996 1.996V24h-3.99M9.5 24.648c0 1.102.893 1.996 1.995 1.996h0a1.995 1.995 0 0 0 1.995-1.996v-1.297a1.995 1.995 0 0 0-1.995-1.995h0A1.995 1.995 0 0 0 9.5 23.351m0-1.995v7.981");
}

</style>
