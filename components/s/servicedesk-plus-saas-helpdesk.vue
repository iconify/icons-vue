<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rmk70zaxj"/><path class="f8vbcwb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:servicedesk-plus-saas-helpdesk" /></template>
<style>
.f8vbcwb2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 23.94a4.68 4.68 0 0 0-4.437-3.182c-.864 0-1.664.25-2.359.659c-.532-3.575-3.586-6.326-7.31-6.326c-.923 0-1.798.19-2.614.498c-.85-3.162-3.708-5.5-7.138-5.5c-4.008 0-7.252 3.183-7.393 7.156a4.64 4.64 0 0 0-3.067-1.17A4.68 4.68 0 0 0 4.5 20.759");
}

.rmk70zaxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.311 30.211v7.701h8.622V22.51h-8.622M11.312 37.912h8.621v-7.701m-8.621 0V22.51h8.621");
}

</style>
