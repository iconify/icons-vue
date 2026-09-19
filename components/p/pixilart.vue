<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fxev6v04x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixilart" /></template>
<style>
.fxev6v04x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.454 42.5h5.341v-6.15h5.142v-6.19h5.501V23.7H42.5V11.67h-5.062V5.5H26.796v6.17h-5.342V5.5H10.821v6.17H5.5V23.7h5.331v6.47h5.322v6.19h5.291z");
}

</style>
