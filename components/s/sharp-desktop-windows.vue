<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jio770bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-desktop-windows" /></template>
<style>
.jio770bgp {
  fill: currentColor;
  d: path("M23 2H1v16h9v2H8v2h8v-2h-2v-2h9zm-2 14H3V4h18z");
}

</style>
