<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgt_35b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vivo-cloud" /></template>
<style>
.jgt_35b6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.783 35.573h23.98c13.015 0 10.838-19.586-2.216-15.243c0-10.876-19.586-10.876-19.586 2.178C2.073 20.33 2.073 35.573 10.783 35.573");
}

</style>
