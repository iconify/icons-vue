<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yazt65l2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transmission-tower-fill-sharp" /></template>
<style>
.yazt65l2g {
  fill: currentColor;
  d: path("m5.051 20.684l1-3v-.001L8.613 10H5v2a1 1 0 0 1-2 0V9a1 1 0 0 1 1-1h5V5c0-.265.105-.52.293-.707l2-2a1 1 0 0 1 1.414 0l2 2A1 1 0 0 1 15 5v3h5a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0v-2h-3.613l2.561 7.683l.001.002l1 2.999a1.001 1.001 0 0 1-1.898.632L16.279 19H7.721l-.772 2.316a1.001 1.001 0 0 1-1.898-.632M13 8V5.414l-1-1l-1 1V8Zm-1 7.764l1.92-3.841L13.279 10h-2.558l-.641 1.923ZM10.382 17l-1.197-2.393L8.387 17Zm3.236 0h1.995l-.798-2.393Z");
}

</style>
