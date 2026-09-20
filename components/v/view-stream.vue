<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmu4-itzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-stream" /></template>
<style>
.fmu4-itzh {
  fill: currentColor;
  d: path("M4 18v-5.5h16V18zm0-6.5V6h16v5.5z");
}

</style>
