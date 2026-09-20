<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erru0zbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-plug-off-sharp" /></template>
<style>
.erru0zbrb {
  fill: currentColor;
  d: path("M10.27 20v-2.654L7 14.077v-5.79h.787V9.72L1.822 3.74l.708-.708l18.4 18.4l-.708.708l-5.642-5.643l-.85.85V20zm6.303-5.738L9.346 7.034V4h1v4h3.308V4h1v4H17v5.835z");
}

</style>
