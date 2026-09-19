<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iniv2ddhp"/><path class="ftysh_byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polygrams" /></template>
<style>
.ftysh_byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.671 10.258l15.327 15.327l7.664-7.664H42.5M23.998 40.913V25.586H8.671");
}

.iniv2ddhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.671 25.585l15.327-15.327c4.232-4.232 11.095-4.232 15.327 0s4.232 11.095 0 15.327L23.998 40.912zc-4.233-4.232-4.233-11.095 0-15.327s11.095-4.232 15.327 0l15.327 15.327");
}

</style>
