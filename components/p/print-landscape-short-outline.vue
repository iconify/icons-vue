<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpnz33i_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-landscape-short-outline" /></template>
<style>
.qpnz33i_k {
  fill: currentColor;
  d: path("M5 6.925V17zm10-2.7q-1.6.725-4.337 1.563T5 6.925V17q3.95-.525 6.538-1.65T15 13.725zM19 19H5v-2h14V6.975h-3v-2h3q.825 0 1.413.588T21 6.975V17q0 .825-.587 1.413T19 19M5 19q-.825 0-1.412-.587T3 17H2v-3h1V9.975H2v-3h1V6.9q0-.8.55-1.362T4.9 4.9q2.75-.275 5.313-1.05t4.112-1.5q.95-.45 1.813.15T17 4.15v9.425q0 .575-.287 1.1t-.863.85q-.975.55-2.4 1.163t-2.937 1.125t-2.975.85T5 19");
}

</style>
