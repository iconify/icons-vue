<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kef83j9cr"/><circle class="z06l1zbux"/><circle class="z38_sn6xt"/><circle class="ehd5wg_2j"/><circle class="knvc0rbuz"/><circle class="mynxyg8fl"/><path class="dn7900buy"/><circle class="eq5fo4bmv"/><path class="wkhihqbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:waistline" /></template>
<style>
.dn7900buy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.607 33.504c-2.548-1.635-2.548-3.163-2.548-4.046c0-2.155 3.29-4.444 6.319-4.444s2.27 2.481 1.934 3.407s-2.902 6.729-3.238 7.654s-.882 2.944.715 2.944c3.014 0 6.897-1.514 7.528-8.706c0 0-5.804 8.538-.513 8.538c5.84 0 6.465-9.127 6.706-13.837");
}

.ehd5wg_2j {
  cx: 17.8px;
  cy: 9.655px;
  r: 0.75px;
  fill: currentColor;
}

.eq5fo4bmv {
  cx: 24.037px;
  cy: 15.762px;
  r: 1.262px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kef83j9cr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.934 4.761c-1.998-.034-4.263.126-5.622.463c-2.144.522-4.022 1.23-4.554 1.707c-.492.447-.513 3.287-.046 5.11c.829 3.193 3.586 5.985 6.757 6.838c4.188 1.124 8.636-.679 10.88-4.413c.903-1.507 1.35-3.303 1.35-5.468c0-1.646-.04-1.791-.568-2.208c-.596-.467-2.976-1.285-5.12-1.753c-.763-.165-1.872-.255-3.077-.276m-4.52 19.726");
}

.knvc0rbuz {
  cx: 20.921px;
  cy: 8.899px;
  r: 0.75px;
  fill: currentColor;
}

.mynxyg8fl {
  cx: 27.162px;
  cy: 8.899px;
  r: 0.75px;
  fill: currentColor;
}

.wkhihqbnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.037 14.5v-3.785M18.262 5.5H9.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-8.668");
}

.z06l1zbux {
  cx: 24.042px;
  cy: 8.149px;
  r: 0.75px;
  fill: currentColor;
}

.z38_sn6xt {
  cx: 30.282px;
  cy: 9.655px;
  r: 0.75px;
  fill: currentColor;
}

</style>
