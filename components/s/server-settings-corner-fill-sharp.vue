<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ck-xb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-settings-corner-fill-sharp" /></template>
<style>
.r4ck-xb2m {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1ZM7.01 6H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M16 13a1 1 0 0 1 2 0v.126a4 4 0 0 1 1.854 1.071l.11-.063a1 1 0 0 1 1 1.732l-.109.063a4.04 4.04 0 0 1 0 2.142l.109.063a1 1 0 0 1-1 1.732l-.11-.063c-.511.52-1.147.89-1.854 1.071V21a1 1 0 0 1-2 0v-.126a3.97 3.97 0 0 1-1.854-1.071l-.11.063a1 1 0 0 1-1-1.732l.109-.063a4.04 4.04 0 0 1 0-2.142l-.109-.063a1 1 0 0 1 1-1.732l.11.063A4 4 0 0 1 16 13.126Zm-6 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1m5.252 2.026l-.001.002a2.01 2.01 0 0 0 .032 2a2 2 0 0 0 3.434-2.055v-.001A2 2 0 0 0 17.001 15h-.002a2 2 0 0 0-1.747 1.026M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
