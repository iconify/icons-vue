<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5-3lngyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensor-window-outline-sharp" /></template>
<style>
.b5-3lngyq {
  fill: currentColor;
  d: path("M5 20.98V3.02h14v17.96zm1-9.48h4.5v-.77h3v.77H18V4.02H6zm0 1v7.48h12V12.5zm0 7.48h12z");
}

</style>
