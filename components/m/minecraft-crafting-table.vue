<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jt3nzbkaa"/><path class="tjy1rabhv"/><path class="cn94r0cet"/><path class="r3mpjib0v"/><path class="ph1y-v_do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minecraft-crafting-table" /></template>
<style>
.cn94r0cet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.243 34.467L24 45V24.066l18.243-10.533zM24 19.286l-9.966-5.753L24 7.779l9.966 5.754zm9.122-.487v20.935M14.878 18.799v20.935m2.821-24.448l9.652-5.572m-6.702 7.638l9.966-5.754m-3.264 5.754l-9.966-5.754m3.264-1.884l9.879 5.703m-19.062 15.52l-3.61-1.816v-2.344l3.61 1.817zm-1.805-8.731v5.479");
}

.jt3nzbkaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45L5.756 34.467V13.533L24 24.066z");
}

.ph1y-v_do {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.231 26.488v1.148l-2.294 3.363v2.393m-6.732-3.715l-3.531-2.038v-4.052l3.531 2.039zm-3.531-2.038v3.023l1.177.679v3.023l1.177.68v3.023l1.177.679v-9.069z");
}

.r3mpjib0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.937 27.813v1.148l2.294.713v2.393");
}

.tjy1rabhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.066L5.756 13.533L24 3l18.243 10.533z");
}

</style>
