<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ptdj15z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-settings-corner-fill" /></template>
<style>
.v8ptdj15z {
  fill: currentColor;
  d: path("M21 9H4v9a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1m-1.146 5.197l.11-.063a1 1 0 0 1 1 1.732l-.109.063a4.04 4.04 0 0 1 0 2.142l.109.063a1 1 0 0 1-1 1.732l-.11-.063c-.511.52-1.147.89-1.854 1.071V21a1 1 0 0 1-2 0v-.126a3.97 3.97 0 0 1-1.854-1.071l-.11.063a1 1 0 0 1-1-1.732l.109-.063a4.04 4.04 0 0 1 0-2.142l-.109-.063a1 1 0 0 1 1-1.732l.11.063A4 4 0 0 1 16 13.126V13a1 1 0 0 1 2 0v.126c.707.182 1.344.55 1.854 1.071m-4.571 1.775l-.032.056a2.01 2.01 0 0 0 .032 2A2 2 0 1 0 17.001 15h-.002c-.704 0-1.355.368-1.716.972");
}

</style>
