<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nemf08bnu"/><path class="q5_zm8bxg"/><path class="kx2t_mv8m"/><path class="abink0bwc"/><ellipse class="p2kixyeyr"/><ellipse class="qzsh5ebvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qq-alt" /></template>
<style>
.abink0bwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.118 39.136l-2.8 2.015c-1.9 1.368-1.16 2.527.198 2.326c7.243-.596 14.52-.678 21.775-.247c1.86.155 1.943-1.151.693-1.88l-3.693-2.155");
}

.kx2t_mv8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.13 31.45c.718 13.929 24.246 13.42 24.003-.247m-4.974-10.339l.965 4.648");
}

.nemf08bnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.982 19.326c1.793-21.639 24.704-17.775 24.151-.099");
}

.p2kixyeyr {
  cx: 28.487px;
  cy: 13.56px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.559px;
  ry: 3.489px;
}

.q5_zm8bxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.982 19.326a31.04 31.04 0 0 0 24.151-.099m0 0c2.015 5.416 4.152 10.214 4.256 14.896c.03 1.35-1.359 2.64-2.425.594l-1.83-3.513M11.982 19.326c-1.604 4.667-3.843 8.998-4.305 13.61c-.446 4.446 1.465 3.283 2.375 1.83l2.079-3.316");
}

.qzsh5ebvl {
  cx: 20.642px;
  cy: 13.56px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.559px;
  ry: 3.489px;
}

</style>
