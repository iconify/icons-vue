<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ogomypb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mindshine" /></template>
<style>
.ogomypb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.52 42.297c-14.14-3.558-12.546-27.817.712-35.03c8.833-4.806 26.751.537 26.17 11.854c-.52 10.12-18.392 25.312-26.881 23.176m11.956-27.092c-11.913-5.164-19.092 15.169-9.43 17.126c7.974 1.615 19.88-12.595 9.43-17.126");
}

</style>
