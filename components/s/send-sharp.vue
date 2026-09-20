<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tunrf6ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-sharp" /></template>
<style>
.tunrf6ble {
  fill: currentColor;
  d: path("M4 18.5v-5.154L9.846 12L4 10.654V5.5L19.423 12z");
}

</style>
