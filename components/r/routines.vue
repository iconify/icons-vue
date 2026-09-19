<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aq0z11bih"/><path class="nl_ttjbxg"/><path class="gb2p8uyak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:routines" /></template>
<style>
.aq0z11bih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.564c11.874 0 21.5-9.626 21.5-21.5s-9.626-21.5-21.5-21.5m0 0q-.756 0-1.5.051");
}

.gb2p8uyak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.5 45.512q.744.051 1.5.052m0-12.093V14.656m-9.408 9.408h18.816");
}

.nl_ttjbxg {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 3.073 3.073;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.459 3.044C9.766 5.128 2.5 13.748 2.5 24.064c0 10.845 8.03 19.815 18.47 21.288");
}

</style>
