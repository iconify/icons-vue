<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wv4j7fbnp"/><rect class="nbsjoep-c"/><path class="za-o81b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:olxro" /></template>
<style>
.nbsjoep-c {
  width: 5.643px;
  height: 21.457px;
  x: 24.612px;
  y: 13.272px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.545px;
}

.wv4j7fbnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.087 24a8.815 8.815 0 0 1-8.793 8.837h0A8.815 8.815 0 0 1 4.5 24h0a8.815 8.815 0 0 1 8.793-8.837h0A8.815 8.815 0 0 1 22.087 24Zm-6.305 0a2.489 2.489 0 1 1-2.489-2.501A2.495 2.495 0 0 1 15.783 24Z");
}

.za-o81b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.78 18.612v3.582l1.798 1.805l-1.798 1.807v3.582h3.564l1.796-1.807l1.798 1.807H43.5v-3.582l-1.796-1.807l1.796-1.805v-3.582h-3.562l-1.798 1.807l-1.796-1.807Z");
}

</style>
