<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="f_imv4qgv"/><circle class="b6igv-c8e"/><circle class="q-ruzlf1m"/><circle class="uuulzwu9v"/><ellipse class="inkv48mvy"/><ellipse class="wtu_foexh"/><circle class="mxy2yvbpr"/><circle class="it0q39kdi"/><circle class="see70bb1x"/><ellipse class="secwxsuvu"/><circle class="ma30fnbmq"/><circle class="wc_dbf9fr"/><circle class="v99l0-baw"/><path class="n1fdnwu0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moon-phase" /></template>
<style>
.b6igv-c8e {
  cx: 34.289px;
  cy: 16.917px;
  r: 3.064px;
}

.f_imv4qgv {
  d: path("M23.94 29.086a6.36 6.36 0 1 1 1.202-3.72q0 .627-.122 1.241");
}

.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.inkv48mvy {
  cx: 41.807px;
  cy: 22.725px;
  rx: 0.985px;
  ry: 1.786px;
}

.it0q39kdi {
  cx: 19.893px;
  cy: 40.978px;
  r: 2.256px;
}

.ma30fnbmq {
  cx: 26.52px;
  cy: 39.261px;
  r: 0.951px;
}

.mxy2yvbpr {
  cx: 27.569px;
  cy: 34.038px;
  r: 2.021px;
}

.n1fdnwu0x {
  d: path("M23.39 45.492c-4.656-6.134-7.19-13.718-7.19-21.532c0-7.749 2.492-15.276 7.08-21.385");
}

.q-ruzlf1m {
  cx: 14.304px;
  cy: 13.125px;
  r: 2.002px;
}

.secwxsuvu {
  cx: 19.073px;
  cy: 5.836px;
  rx: 1.601px;
  ry: 0.8px;
}

.see70bb1x {
  cx: 9.335px;
  cy: 30.028px;
  r: 1.193px;
}

.uuulzwu9v {
  cx: 29.671px;
  cy: 9.321px;
  r: 1.472px;
}

.v99l0-baw {
  cx: 25.173px;
  cy: 28.051px;
  r: 1.392px;
}

.wc_dbf9fr {
  cx: 19.273px;
  cy: 22.994px;
  r: 1.414px;
}

.wtu_foexh {
  cx: 40.144px;
  cy: 32.413px;
  rx: 1.019px;
  ry: 1.601px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
