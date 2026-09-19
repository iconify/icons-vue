<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgii_rqhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:settings-input-hdmi" /></template>
<style>
.qgii_rqhb {
  fill: currentColor;
  d: path("M18 7V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v3H5v6l3 6v3h8v-3l3-6V7zM8 4h8v3h-2V5h-1v2h-2V5h-1v2H8z");
}

</style>
