<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="qqbuy0chh"/><circle class="f_v_dfbgn"/><path class="ue0g45bdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meine-aok" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.qqbuy0chh {
  d: path("m28.767 26.868l-4.726 2.729m-.171-9.909v15.398m9.816.23h-19.64m9.644-5.846l-5.132-2.963");
}

.ue0g45bdm {
  d: path("m20.825 12.283l3.06-3.06l2.882 2.883m.109.12l.01.01a4.255 4.255 0 0 1 .015 6.021q-.004.006-.015.005a4.26 4.26 0 0 1-6.112-5.936M10.623 25.609l-1.12-4.18l3.938-1.054m.158-.035l.014-.004a4.26 4.26 0 1 1-2.979 5.338m23.623-5.309l4.138 1.265l-1.192 3.898m-.054.152l-.005.014a4.26 4.26 0 1 1-2.948-5.355");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
