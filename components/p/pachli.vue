<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgmamqbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pachli" /></template>
<style>
.xgmamqbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.216 4.5h8.008v39h-8.008zm16.7 21.734c6.002 0 10.868-4.865 10.868-10.867S32.918 4.5 26.916 4.5h-8.691v21.734zm2.757-.385V4.886");
}

</style>
