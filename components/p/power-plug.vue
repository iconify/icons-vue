<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_i-06bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-plug" /></template>
<style>
.z_i-06bgd {
  fill: currentColor;
  d: path("M10.27 20v-2.654L7 14.077V9.621q0-.669.475-1.145T8.615 8h1.231l-.5.5V4h1v4h3.308V4h1v4.5l-.5-.5h1.23q.667 0 1.142.476T17 9.62v4.457l-3.27 3.27V20z");
}

</style>
