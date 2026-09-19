<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w19j_566a"/><path class="wgzi318wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proton-wallet" /></template>
<style>
.w19j_566a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.28h17.48c6.468 0 11.712 5.243 11.712 11.711v15.016m-23.738 0l5.98-6.793");
}

.wgzi318wz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.505 34.959h7.718c2.78 0 5.036-2.41 5.036-5.38s-2.255-5.381-5.036-5.381H5.505v-12.3A3.904 3.904 0 0 1 9.41 7.992h17.475c8.624 0 15.616 6.992 15.616 15.616v12.493a3.904 3.904 0 0 1-3.904 3.905H9.409a3.904 3.904 0 0 1-3.904-3.905zm10.192-5.363a2.863 2.863 0 1 0-5.726 0a2.863 2.863 0 0 0 5.726 0");
}

</style>
