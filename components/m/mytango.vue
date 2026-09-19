<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vnzh7pboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mytango" /></template>
<style>
.vnzh7pboe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.666 24c0 6.612-5.184 11.973-11.58 11.975S4.503 30.62 4.5 24.007S9.678 12.03 16.074 12.025c6.396-.006 11.585 5.35 11.592 11.962zm3.253-11.524c5.915 5.334 5.924 17.998 0 23.109m8.141-23.109c5.915 5.334 5.925 17.998 0 23.109");
}

</style>
