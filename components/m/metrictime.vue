<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="j5ahyib_q"/><path class="di3ax78fx"/><circle class="jxerzv-rs"/><path class="ga21_-bqx"/><circle class="qyr00-b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metrictime" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.di3ax78fx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3v2m0 38v2m19.972-14.511l-1.902-.618m-6.902 9.5l1.175 1.618m7.629-23.478l-1.902.618M36.343 7.011l-1.175 1.618M12.832 39.371l-1.175 1.618M5.93 29.871l-1.902.618m0-12.978l1.902.618m5.727-11.118l1.175 1.618M24 25.5V35m14.266-6.365l-12.841-4.172m4.82-7.796a2.35 2.35 0 0 0 2.358 2.358a2.276 2.276 0 0 0 2.271-2.358v-2.359a2.33 2.33 0 0 0-2.27-2.358a2.406 2.406 0 0 0-2.359 2.358Zm4.105-3.844l-3.494 5.328");
}

.ga21_-bqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.126 18.413a2.74 2.74 0 0 0 2.096.612h.262a2.31 2.31 0 0 0 2.271-2.271h0a2.31 2.31 0 0 0-2.271-2.271h-2.358v-2.446h4.629m8.996 6.988a1.75 1.75 0 0 0 1.747-1.747h0a1.75 1.75 0 0 0-1.747-1.747h0a1.75 1.75 0 0 0 1.747-1.747h0a1.75 1.75 0 0 0-1.747-1.747m-2.882.612a2.97 2.97 0 0 1 2.184-.612h.698m-2.882 6.376a2.84 2.84 0 0 0 2.184.612h.698");
}

.j5ahyib_q {
  cx: 24px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jxerzv-rs {
  cx: 20.812px;
  cy: 18.239px;
  r: 0.873px;
  fill: currentColor;
}

.qyr00-b6z {
  cx: 20.812px;
  cy: 13.61px;
  r: 0.873px;
  fill: currentColor;
}

</style>
