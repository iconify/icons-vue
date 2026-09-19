<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qg5wvmier"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zfont" /></template>
<style>
.qg5wvmier {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.16 30.219h29.679V42.5H9.16zm29.68-5.117H9.16l-3.07 5.117h35.82zm-7.669-4.108v1.038H16.829L31.171 5.5H16.829v1.023");
}

</style>
