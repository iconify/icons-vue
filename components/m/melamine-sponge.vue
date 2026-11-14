<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eck0wpbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:melamine-sponge" /></template>
<style>
.eck0wpbyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.02 4.924q1.877-1.564 4.815-.095q2.062 1.031 3.185.095q1.877-1.564 4.815-.095q2.062 1.031 3.185.095q.057-.047.121-.083q.065-.035.136-.057q.07-.022.144-.03t.147-.001t.144.028t.137.055q.065.034.122.081q.058.046.105.103q.096.114.14.257q.044.142.031.291q-.014.148-.083.281q-.069.132-.184.227q-1.877 1.564-4.815.095q-2.062-1.031-3.185-.095q-1.877 1.564-4.815.095Q6.103 5.14 4.98 6.076q-.057.047-.121.083q-.065.035-.136.057q-.07.022-.144.03t-.147.001t-.144-.028t-.137-.055t-.122-.081q-.058-.046-.105-.103t-.083-.121t-.057-.136q-.022-.07-.03-.144t-.001-.147t.028-.144t.055-.137t.081-.122q.046-.058.103-.105M17.5 9.25h-11q-1.76 0-3.005 1.245T2.25 13.5V16q0 1.76 1.245 3.005T6.5 20.25h11q1.76 0 3.005-1.245T21.75 16v-2.5q0-1.76-1.245-3.005T17.5 9.25");
}

</style>
