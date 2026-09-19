<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gzqf3jgma"/><circle class="v5gj_pjtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vimpay" /></template>
<style>
.gzqf3jgma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.858 12.068v9.401m-3.005-9.4L7.738 21.47l-3.114-9.401m12.867 9.39v-9.391l4.701 9.401l4.7-9.387v9.387m-6.464 14.452v-9.4h3.078c1.74 0 3.15 1.413 3.15 3.156s-1.41 3.158-3.15 3.158h-3.078m21.489-6.313l-3.114 4.701l-3.114-4.701m3.114 9.402v-4.701m-5.568 1.586H29.07m-1.032 3.115l3.114-9.402l3.115 9.402M4.5 26.509h9.423v9.423H4.5z");
}

.v5gj_pjtm {
  cx: 38.85px;
  cy: 16.768px;
  r: 4.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
