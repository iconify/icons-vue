<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ye7y7d_5b"/><path class="awc7-pbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nrf-connect" /></template>
<style>
.awc7-pbgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.234 36.738c-7.122 11.738-18.053.587-16.603-6.33c1.252-5.978 3.785-12.004 9.59-16.633c5.065-4.04 18.647 1.734 10.844 15.852");
}

.ye7y7d_5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.712 10.803c5.4-10.482 17.114-.999 15.665 5.918c-1.253 5.978-3.785 12.004-9.59 16.633c-5.065 4.04-19.144.13-11.125-14.65");
}

</style>
