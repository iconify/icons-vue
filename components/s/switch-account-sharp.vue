<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv4otbcbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-account-sharp" /></template>
<style>
.pv4otbcbx {
  fill: currentColor;
  d: path("M16.125 10.125Q17 9.25 17 8t-.875-2.125T14 5t-2.125.875T11 8t.875 2.125T14 11t2.125-.875M6 18V2h16v16zm-4 4V6h2v14h14v2zm6-6h12q-1.05-1.425-2.637-2.212T14 13t-3.363.788T8 16");
}

</style>
