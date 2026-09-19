<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b9dg0nbya"/><path class="bp81bg9uo"/><circle class="d_uf4acuc"/><circle class="q0ldycb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tradingview-alt" /></template>
<style>
.b9dg0nbya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.735 20.11a9.475 9.475 0 0 1 18.445-1.46m.001-.001a6.5 6.5 0 0 1 6.057-.381a6.38 6.38 0 0 1 3.688 5.356");
}

.bp81bg9uo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.926 23.624a5.452 5.452 0 0 1-1.128 10.503m0 0H10.864m.871-14.017a7.024 7.024 0 0 0-.87 14.016m19.282-6.796l7.454-8.204m-16.787 2.717l6.5 5.7M6.08 31.606l11.716-9.83");
}

.d_uf4acuc {
  cx: 19.334px;
  cy: 20.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.q0ldycb5r {
  cx: 28.836px;
  cy: 28.836px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
