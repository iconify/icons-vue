<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n5teep-mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:status2" /></template>
<style>
.n5teep-mv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.998 4.628a9.36 9.36 0 0 1 8.467 10.17c-.47 5.147-4.855 8.124-10.17 8.467c0 0-2.98.427-8.668-1.476a20.15 20.15 0 0 0-11.018-.31S17.153 2.785 34 4.628M14.002 43.372a9.36 9.36 0 0 1-8.467-10.17c.47-5.147 4.855-8.124 10.17-8.467c0 0 2.98-.427 8.668 1.476a20.15 20.15 0 0 0 11.018.31s-4.544 18.694-21.39 16.851");
}

</style>
