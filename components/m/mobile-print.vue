<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xl54vccgd"/><path class="hqycr0b3u"/><circle class="ec6j28s9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-print" /></template>
<style>
.ec6j28s9h {
  cx: 39.461px;
  cy: 25.079px;
  r: 0.75px;
  fill: currentColor;
}

.hqycr0b3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.163 41.306V31.069H10.81v10.237m18.483-28.414V6.694H11.604v14.137h24.792v-7.939zm0-6.198l7.103 6.198m-10.516 0H15.573m16.715 3.621H15.573");
}

.xl54vccgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 20.831h39v20.475h-39z");
}

</style>
