<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3qh_ue0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-1" /></template>
<style>
.q3qh_ue0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 19.239h8.151m-4.075 12.54v-12.54m7.135-.157v12.697m-.001-5.329c0-1.725 1.411-3.136 3.136-3.136s3.135 1.411 3.135 3.135v5.173m8.859-1.41c-.47.94-1.567 1.567-2.665 1.567a3.144 3.144 0 0 1-3.135-3.135v-2.038c0-1.724 1.411-3.135 3.135-3.135s3.135 1.41 3.135 3.135v1.097h-6.27m8.221 7.878H43.5m-9.529-23.162h4.409v19.975");
}

</style>
