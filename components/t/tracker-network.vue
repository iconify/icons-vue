<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="veoqjsaod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tracker-network" /></template>
<style>
.veoqjsaod {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16.986h25.673V24H23.19m1.987 0l4.294 7.014M11.234 16.986v14.028m8.417-14.028v14.028M43.5 16.986v14.028l-9.119-14.028v14.028");
}

</style>
