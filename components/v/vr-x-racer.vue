<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="njfpb5ugk"/><circle class="e7rr70b9y"/><circle class="g3v4_kbpf"/><path class="nnx69ebth"/></g><path class="z_2z65a9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vr-x-racer" /></template>
<style>
.e7rr70b9y {
  cx: 19.028px;
  cy: 11.075px;
  r: 2.119px;
}

.g3v4_kbpf {
  cx: 28.972px;
  cy: 11.075px;
  r: 2.119px;
}

.njfpb5ugk {
  d: path("M31.777 5.5H16.223a.97.97 0 0 0-.969.969v9.676a.97.97 0 0 0 .969.969h3.396c2.736 0 2.396-4.426 4.38-4.426s1.513 4.426 4.382 4.426h3.396a.97.97 0 0 0 .969-.97V6.47a.97.97 0 0 0-.97-.969");
}

.nnx69ebth {
  d: path("m14.965 23.645l-4.089 2.283l-.595 6.681l-3.329 6.396V42.5h2.901l.737-2.449l2.045-2.639l.095-3.471l3.352-3.305l1.103-5.891zm4.178 5.109l-2.704-.021m-6.158 3.876l2.449 1.332M24 22.037l3.555 2.04l.891 6.297l-.737 2.663l5.183 5.469L24 39.599l-8.892-1.093l5.183-5.469l-.737-2.663l.675-6.27zm9.035 1.608l4.089 2.283l.595 6.681l3.329 6.396V42.5h-2.901l-.737-2.449l-2.045-2.639l-.095-3.471l-3.352-3.305l-1.103-5.891zm-4.178 5.109l2.704-.021m6.158 3.876l-2.449 1.332m-13.014 3.534h3.488");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_2z65a9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.31 35.834l5.69-.881l5.69.881");
}

</style>
