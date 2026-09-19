<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="njp-s1xqv"/><circle class="xw2voabhm"/><circle class="ynzydr0hv"/><circle class="asihhgnyt"/><circle class="qdexb9h3z"/><circle class="w8m4x0blb"/><circle class="sb93s2biw"/><circle class="ohs9jgmys"/><circle class="cfxxj7jve"/><circle class="lkft19slo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tk-husteblume" /></template>
<style>
.asihhgnyt {
  cx: 26.938px;
  cy: 11.568px;
  r: 0.75px;
  fill: currentColor;
}

.cfxxj7jve {
  cx: 28.95px;
  cy: 31.879px;
  r: 0.75px;
  fill: currentColor;
}

.lkft19slo {
  cx: 32.606px;
  cy: 23.085px;
  r: 0.75px;
  fill: currentColor;
}

.njp-s1xqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.643 24.717c-1.542 9.245 1.37 12.69 6.147 17.783m-7.847-19.465h-5.974m-.019.052l-5.113 2.852m5.043-2.989l-5.026-3.002m11.751 1.539l-4.225-4.224m-.05.023l-5.633-1.598m5.681 1.452l-1.432-5.676m7.221 9.397v-5.974m-.053-.02l-2.852-5.112m2.99 5.044l3-5.027m-.912 13.313h5.974m.02-.053l5.112-2.852m-5.043 2.99l5.026 3m-11.751-1.538l4.225 4.224m.051-.023l5.632 1.598m-5.681-1.452l1.432 5.677m.358-19.248l4.224-4.225m-.023-.051L33.494 5.5m-1.452 5.68l5.676-1.431");
}

.ohs9jgmys {
  cx: 20.14px;
  cy: 23.052px;
  r: 0.75px;
  fill: currentColor;
}

.qdexb9h3z {
  cx: 20.167px;
  cy: 10.595px;
  r: 0.75px;
  fill: currentColor;
}

.sb93s2biw {
  cx: 7.677px;
  cy: 23.052px;
  r: 0.75px;
  fill: currentColor;
}

.w8m4x0blb {
  cx: 11.334px;
  cy: 14.24px;
  r: 0.75px;
  fill: currentColor;
}

.xw2voabhm {
  cx: 40.34px;
  cy: 12.272px;
  r: 0.75px;
  fill: currentColor;
}

.ynzydr0hv {
  cx: 34.949px;
  cy: 8.135px;
  r: 0.75px;
  fill: currentColor;
}

</style>
