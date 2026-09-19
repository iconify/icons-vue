<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vij-ywbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-camera-roll" /></template>
<style>
.vij-ywbne {
  fill: currentColor;
  d: path("M14 5V3h-3V1H5v2H2v19h12v-2h8V5zm-2 13h-2v-2h2zm0-9h-2V7h2zm4 9h-2v-2h2zm0-9h-2V7h2zm4 9h-2v-2h2zm0-9h-2V7h2z");
}

</style>
