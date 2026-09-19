<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ns4fpkzjl"/><rect class="hqup7jbmf"/><rect class="pycvop71v"/><path class="kw6ea75gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sodexo" /></template>
<style>
.hqup7jbmf {
  width: 3.94px;
  height: 5.221px;
  x: 13.36px;
  y: 21.39px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.97px;
  ry: 1.97px;
}

.kw6ea75gx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.124 26.17c.36.302.748.44 1.62.44h.442c.72 0 1.303-.584 1.303-1.305h0c0-.72-.583-1.305-1.303-1.305h-.884A1.303 1.303 0 0 1 8 22.695h0c0-.721.583-1.305 1.302-1.305h.442c.873 0 1.261.138 1.62.44m17.478 3.786a1.97 1.97 0 0 1-1.712.994h0a1.97 1.97 0 0 1-1.97-1.97v-1.28a1.97 1.97 0 0 1 1.97-1.97h0a1.97 1.97 0 0 1 1.97 1.97V24h-3.94m-1.99-.64a1.97 1.97 0 0 0-1.97-1.97h0a1.97 1.97 0 0 0-1.97 1.97v1.28a1.97 1.97 0 0 0 1.97 1.97h0a1.97 1.97 0 0 0 1.97-1.97m.001 1.97v-7.88");
}

.ns4fpkzjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4zm28.988 1.79l-3.94 5.22m3.94 0l-3.94-5.22");
}

.pycvop71v {
  width: 3.94px;
  height: 5.221px;
  x: 36.06px;
  y: 21.39px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.97px;
  ry: 1.97px;
}

</style>
