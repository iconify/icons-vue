<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p1v74wbpd"/><path class="stwv60w_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:top-hat" /></template>
<style>
.p1v74wbpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.375 4.5h29.25v9.75H9.375zm9.75 29.25h9.75v9.75h-9.75z");
}

.stwv60w_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.875 4.5V24h-9.75v-9.75");
}

</style>
