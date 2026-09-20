<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhht-ibwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-2-sharp" /></template>
<style>
.fhht-ibwb {
  fill: currentColor;
  d: path("M20 20V4zM4 20h9.5V4H4zm10.5 0H20v-7.5h-5.5zm0-8.5H20V4h-5.5z");
}

</style>
