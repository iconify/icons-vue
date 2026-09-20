<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_bjwtb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:panorama-horizontal-outline-sharp" /></template>
<style>
.f_bjwtb2s {
  fill: currentColor;
  d: path("M4 17.65q1.95-.575 3.963-.862T12 16.5t4.038.288T20 17.65V6.375q-1.95.575-3.963.85T12 7.5t-4.038-.275T4 6.375zM2.025 20.5V3.475q1.875.875 4.5 1.45t5.5.575t5.5-.575t4.5-1.45V20.5q-1.875-.875-4.5-1.437t-5.5-.563t-5.5.563t-4.5 1.437M12 12");
}

</style>
