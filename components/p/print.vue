<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b9qu1qbix"/><path class="ma0x8lbml"/><path class="hbk4b3baz"/><circle class="l2lh_y_vw"/><circle class="pkd37ebwb"/><circle class="r0uqx6b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:print" /></template>
<style>
.b9qu1qbix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.517 35.415H6.403a.903.903 0 0 1-.903-.903V21.008c0-.498.404-.902.903-.902h35.194c.499 0 .903.404.903.902v13.504a.903.903 0 0 1-.903.903h-8.114");
}

.hbk4b3baz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.483 6.433v4h4");
}

.l2lh_y_vw {
  cx: 39.852px;
  cy: 22.898px;
  r: 0.75px;
  fill: currentColor;
}

.ma0x8lbml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.517 31.437h18.966v10.13H14.517zm0-11.331V6.433h14.966l4 4v9.673");
}

.pkd37ebwb {
  cx: 36.835px;
  cy: 22.898px;
  r: 0.75px;
  fill: currentColor;
}

.r0uqx6b2j {
  cx: 33.819px;
  cy: 22.898px;
  r: 0.75px;
  fill: currentColor;
}

</style>
