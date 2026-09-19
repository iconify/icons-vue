<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr7q-8b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-quilt" /></template>
<style>
.qr7q-8b6x {
  fill: currentColor;
  d: path("M21 5v6.5H9.33V5zm-6.33 14v-6.5H9.33V19zm1-6.5V19H21v-6.5zM8.33 19V5H3v14z");
}

</style>
