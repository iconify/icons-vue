<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqq9sqblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-1x-mobiledata" /></template>
<style>
.oqq9sqblt {
  fill: currentColor;
  d: path("M5 7h2c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1s-1-.45-1-1V9H5c-.55 0-1-.45-1-1s.45-1 1-1m10.83 4.72l1.92-3.21A.997.997 0 0 0 16.9 7a.99.99 0 0 0-.86.49l-1.37 2.28l-1.38-2.29c-.18-.3-.5-.48-.85-.48c-.78 0-1.26.85-.86 1.51l1.92 3.21l-2.26 3.77c-.4.67.08 1.51.86 1.51c.35 0 .68-.18.86-.49l1.71-2.85l1.71 2.85c.18.3.51.49.86.49h.01c.78 0 1.26-.85.86-1.51z");
}

</style>
