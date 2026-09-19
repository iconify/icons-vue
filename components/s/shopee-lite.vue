<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b76sdtoti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shopee-lite" /></template>
<style>
.b76sdtoti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.558 33.5v8h4m5-4a7 7 0 1 1-14 0a7 7 0 0 1 14 0m-25.971-1.517c1.154.865 2.308 1.153 4.615 1.153h1.154a3.75 3.75 0 1 0 0-7.5H19.76a3.75 3.75 0 1 1 0-7.5h1.154c2.596 0 3.75.289 4.615 1.154m-15.12-6.517V14.16c0-5.887 4.773-10.66 10.66-10.66s10.66 4.773 10.66 10.66v2.613m-1.105 25.694a4 4 0 0 1-.51.033h-18.11a4 4 0 0 1-3.975-3.537l-2.587-22.19h31.23L35.07 30.535");
}

</style>
