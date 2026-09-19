<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="liv3fddvu"/><circle class="g4h1trbkj"/><path class="aelhmzbvx"/><path class="weameub_n"/><circle class="lwj17bcql"/><path class="g4f2libfv"/><path class="ryv-vcx4m"/><circle class="o01-hbbkh"/><path class="sgw71xbtc"/><path class="k1m1dpbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ubs-banking" /></template>
<style>
.aelhmzbvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.441 38.677a2.65 2.65 0 1 0 0-5.298c-1.463 0-2.281 1.134-2.81 2.649");
}

.g4f2libfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.933 34.456a2.65 2.65 0 0 0-4.06-3.406c-.94 1.12-.597 2.477.224 3.856");
}

.g4h1trbkj {
  cx: 24.09px;
  cy: 37.449px;
  r: 5.641px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k1m1dpbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.661 30.397a2.65 2.65 0 0 0 4.06-3.406c-.941-1.12-2.336-1.019-3.836-.45m-2.981 9.628l2.16-1.813m28.755-20.637l.938-.787m.644 2.672L35.1 11.67m-1.257 4.546l2.255 1.321l-.909-2.45m-2.332 5.169l6.482-5.439m-7.126 2.767l-.938.786m2.52 1.099l-3.301-3.934");
}

.liv3fddvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.09 3.5v28.309m-1.791-1.472h3.583");
}

.lwj17bcql {
  cx: 36.695px;
  cy: 31.637px;
  r: 5.641px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o01-hbbkh {
  cx: 11.305px;
  cy: 31.637px;
  r: 5.641px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ryv-vcx4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.339 30.397a2.65 2.65 0 0 1-4.06-3.406c.941-1.12 2.336-1.019 3.836-.45m2.981 9.628l-2.16-1.813M11.181 13.719l-.938-.787m-.644 2.672L12.9 11.67m1.257 4.546l-2.255 1.321l.909-2.45m2.332 5.169l-6.482-5.439m7.126 2.767l.938.786m-2.52 1.099l3.301-3.934m19.806-5.72L15.626 28.011m2.279.426l-2.303-2.744");
}

.sgw71xbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.067 34.456a2.65 2.65 0 0 1 4.06-3.406c.94 1.12.597 2.477-.224 3.856");
}

.weameub_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.74 38.677a2.65 2.65 0 1 1 0-5.298c1.463 0 2.281 1.134 2.81 2.649M24.09 44.5v-2.82M21.417 6.387V5.163m-2.461 1.224h5.134m-2.673 3.884l-2.461-.878l2.461-.878m-2.461 5.109V5.163m2.461 7.237v1.224M18.956 12.4h5.134M10.688 9.815l21.686 18.196m-2.279.426l2.303-2.744");
}

</style>
