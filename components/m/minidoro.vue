<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nzpfhlbcf"/><path class="zoq2jr_gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minidoro" /></template>
<style>
.nzpfhlbcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.799 17.882c5.61-6.24 17.88-7.34 19.605 5.71c1.112 8.415-7.527 16.622-19.605 16.78c-9.573.123-19.729-7.756-19.285-17.014c.63-13.135 16.374-11.578 19.285-5.477");
}

.zoq2jr_gk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.799 17.882c1.754-3.466 4.324-6.27 9.322-7.108M17.944 7.628c6.974 2.334 6.823 5.854 5.855 10.254c-1.112-3.314-3.575-5.951-9.176-7.02m9.176 9.614v6.902m0 0l6.321 7.02");
}

</style>
