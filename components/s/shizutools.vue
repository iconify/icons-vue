<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sqkt3lb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shizutools" /></template>
<style>
.sqkt3lb4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.936 7.083l8.021 8.022a.59.59 0 0 1 0 .838l-4.015 4.015a.59.59 0 0 1-.838 0l-8.02-8.02a12.525 12.525 0 0 0 2.087 14.955a12.53 12.53 0 0 0 13.083 2.942l12.143 12.143a1.774 1.774 0 0 0 2.515 0l5.065-5.066a1.774 1.774 0 0 0 0-2.515L29.835 22.255A12.53 12.53 0 0 0 26.893 9.17a12.53 12.53 0 0 0-14.957-2.088Z");
}

</style>
