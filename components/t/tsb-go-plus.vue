<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rkaysib1z"/><path class="kult95gfi"/><path class="pl6ts3bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tsb-go-plus" /></template>
<style>
.kult95gfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.518 37.955V17.068h8.53");
}

.pl6ts3bhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.518 34.608h15.917c3.12 0 5.032-.995 5.032-3.684s-1.912-3.709-5.032-3.684l-5.456.043c-3.12.024-5.032-.995-5.032-3.684s1.912-3.684 5.032-3.684H42.3");
}

.rkaysib1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.995 24.081c3.16-2.412 2.757-6.958 1.993-8.963c-.91-2.385-3.28-5.073-7.676-5.073H4.5v7.023h6.925v20.887h24.753c5.32 0 7.322-3.433 7.322-7.15s-1.329-5.525-3.505-6.724");
}

</style>
