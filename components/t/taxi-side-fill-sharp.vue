<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6r_nvbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-side-fill-sharp" /></template>
<style>
.h6r_nvbuu {
  fill: currentColor;
  d: path("M12 3a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2ZM2 12c0-.265.105-.52.293-.707l5-5A1 1 0 0 1 8 6h5c.265 0 .52.105.707.293L18.414 11H21a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0H9.829a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1Zm6.414-4L4 12.414V13h5V8Zm8.879 4.707L12.586 8H11v5h6.586l-.291-.291ZM6.291 18.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
