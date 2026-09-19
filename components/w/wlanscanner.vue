<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mco-mcf_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wlanscanner" /></template>
<style>
.mco-mcf_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 18.4c10.5-10.3 28.3-10.3 39-.1m-32.1 7a18.51 18.51 0 0 1 25.2-.2M19 32.5h10l-5.1 4.8Z");
}

</style>
