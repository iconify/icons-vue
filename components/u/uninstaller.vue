<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_ddbtk1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uninstaller" /></template>
<style>
.l_ddbtk1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.37 21.48v18.377m-7.33-18.376v18.377M16.71 21.48v18.377m14.208-27.969V7.91c.001-2.812.08-3.41-2.732-3.41h-8.373c-2.812 0-2.732.598-2.732 3.41v3.98m20.295 5.844H7.354v-5.728h33.293v5.728zv23.25c0 1.394-.75 2.517-1.68 2.517H12.423c-.93 0-1.678-1.123-1.678-2.518v-23.25");
}

</style>
