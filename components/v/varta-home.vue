<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_o70jt8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:varta-home" /></template>
<style>
.r_o70jt8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.007 35.518V43.5h6.842v-5.702h4.56V43.5h6.843v-7.982m3.991-1.141L25.13 23.544L12.015 34.377m2.229-5.289a3.42 3.42 0 1 1 5.24-4.398m1.496-1.114l1.351-1.318m-4.921-.579l.097-1.865m-3.827 3.055l-1.447-1.64m-.483 5.017l-1.993-.065m3.119 4.052l-1.382 1.158m6.793-26.777l6.842 13.114L31.971 4.5");
}

</style>
