<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tz951kbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polar-beat" /></template>
<style>
.tz951kbtk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 0 0 4.975 14H26a2.5 2.5 0 0 1 0 5H3.115a21.5 21.5 0 0 0-.615 5c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24h0c0-11.874-9.626-21.5-21.5-21.5");
}

</style>
