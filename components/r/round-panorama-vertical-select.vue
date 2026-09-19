<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2w6475sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-panorama-vertical-select" /></template>
<style>
.d2w6475sn {
  fill: currentColor;
  d: path("M18.5 12c0-3.89.84-6.95 1.43-8.69A.993.993 0 0 0 18.98 2H5c-.68 0-1.16.66-.95 1.31C4.74 5.36 5.5 8.1 5.5 12c0 3.87-.76 6.66-1.45 8.69c-.21.65.27 1.31.95 1.31h14c.68 0 1.17-.66.95-1.31c-.68-2.03-1.45-4.83-1.45-8.69");
}

</style>
