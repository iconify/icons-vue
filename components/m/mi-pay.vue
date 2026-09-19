<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qfh9ncb0t"/><g class="y9tr6bcfx"><path class="hs3gpbbsy"/><path class="blyeyg79i"/></g><path class="lywm_rb0h"/><path class="fto1rpb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-pay" /></template>
<style>
.blyeyg79i {
  d: path("M33.429 31.169v3.849a2.34 2.34 0 0 1-2.333 2.333h0a2.34 2.34 0 0 1-2.333-2.333v-3.85");
}

.fto1rpb4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 43.5h25a3 3 0 0 0 3-3v-33a3 3 0 0 0-3-3h-25a3 3 0 0 0-3 3v33a3 3 0 0 0 3 3");
}

.hs3gpbbsy {
  d: path("M33.429 35.018v3.15a2.34 2.34 0 0 1-2.333 2.332h0c-.7 0-1.283-.233-1.633-.7");
}

.lywm_rb0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.571 37.407v-8.64h2.808c1.62 0 2.916 1.296 2.916 2.916S19 34.6 17.38 34.6h-2.808");
}

.qfh9ncb0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.624 12.665l6.681 7.3L33.376 7.5M16.71 25.642V15.136m10.692 10.506V13.978m5.833 0v11.664m-6.495 9.376a2.34 2.34 0 0 1-2.333 2.333h0a2.34 2.34 0 0 1-2.333-2.333V33.5a2.34 2.34 0 0 1 2.333-2.332h0A2.34 2.34 0 0 1 26.74 33.5m0 3.851v-6.182");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
