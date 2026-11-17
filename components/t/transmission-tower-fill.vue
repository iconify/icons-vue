<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym9jm3bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transmission-tower-fill" /></template>
<style>
.ym9jm3bnf {
  fill: currentColor;
  d: path("m5.051 20.684l1-3v-.001L8.613 10H6a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0v-1a3 3 0 0 1 3-3h3V6c0-.505.141-.998.365-1.447c.235-.469.558-.89.928-1.26A2.4 2.4 0 0 1 12 2.586a2.4 2.4 0 0 1 1.707.707c.37.37.693.791.928 1.26c.224.449.365.942.365 1.447v2h3a3 3 0 0 1 3 3v1a1 1 0 0 1-2 0v-1a1 1 0 0 0-1-1h-2.613l2.561 7.683l.001.002l1 2.999a1.001 1.001 0 0 1-1.898.632L16.279 19H7.721l-.772 2.316a1.001 1.001 0 0 1-1.898-.632M13 8V6c0-.193-.069-.382-.154-.553a2.9 2.9 0 0 0-.553-.74a.414.414 0 0 0-.586 0C11.395 5.02 11 5.532 11 6v2Zm-1 7.764l1.92-3.841L13.279 10h-2.558l-.641 1.923ZM10.382 17l-1.197-2.393L8.387 17Zm3.236 0h1.995l-.798-2.393Z");
}

</style>
