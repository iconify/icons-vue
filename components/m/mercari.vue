<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ig6bo0f4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mercari" /></template>
<style>
.ig6bo0f4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.154 43.5V14.991L22.408 43.5l14.255-28.509V43.5M33.3 9.663L34.684 4.5l5.164 1.383l-1.384 5.164z");
}

</style>
