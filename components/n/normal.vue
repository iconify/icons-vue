<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="vphi7y-ue"/><path class="xevlf_bsa"/><path class="t_h_8lbei"/><path class="yze-o9wex"/><circle class="v1yablvhb"/><circle class="bsfzcpbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:normal" /></template>
<style>
.bsfzcpbls {
  cx: 27.233px;
  cy: 16.384px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.t_h_8lbei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.475 20.706s.27-5.784-1.817-8.228s-4.342-2.958-6.796-2.865c-2.356.089-5.025 1.59-6.156 3.658c-1.05 1.919-1.005 4.681-1.047 7.173c-.049 2.94.437 8.132 1.621 10.824c.785 1.783 2.932 1.388 3.696 2.609c.76 1.214.794 2.63.28 3.832c-.665 1.555-3.43 2.602-4.315 3.725s-1.107 1.095-1.107 1.095");
}

.v1yablvhb {
  cx: 21.45px;
  cy: 16.479px;
  r: 0.75px;
  fill: currentColor;
}

.vphi7y-ue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.502 20.242s11.599.844 10.91 4.432s-11.511-.078-11.511-.078");
}

.xevlf_bsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.42 25.58s.263 1.42.628 1.928s.884.867.884.867s-1.292 1.079-2.818 1.052s-2.727-1.094-4.226-1.582c-1.379-.448-2.531-2.268-2.531-2.268m8.166 3.848s.238 1.754-.31 2.42c-.52.63-1.618.399-2.302.847c-.34.223-.836.516-.938.949c-.073.312.303.914.303.914l.687 1.917s2.187 1.352 3.362 2.47c1.99 1.893 2.256 3.464 2.256 3.464");
}

.yze-o9wex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.256 37.709s1.543.685 3.21.785c1.629.098 3.497-1.93 3.497-1.93m-4.2-18.966c.515-.674.464-1.725-.078-2.377c-.65-.783-2.06-1.164-2.894-.583c-.76.528-.642 1.626-.402 2.52c.111.414.537.72.931.89c.824.355 1.899.262 2.443-.45m5.917-.23c.515-.674.086-2.08-.456-2.732c-.649-.783-1.854-.676-2.689-.096c-.76.528-.665 1.105-.425 1.999c.111.414.325.898.719 1.068c.823.355 2.307.474 2.851-.239");
}

</style>
