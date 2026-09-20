<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6__zo5yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mic-external-on-outline-sharp" /></template>
<style>
.n6__zo5yr {
  fill: currentColor;
  d: path("M4.8 7q-.375-.425-.587-.925T4 5q0-1.25.875-2.125T7 2t2.125.875T10 5q0 .575-.213 1.075T9.2 7zM6 22v-4H5L4 8h6L9 18H8v2h4V2h8v20h-2V4h-4v18zm.8-6h.4l.6-6H6.2zm.4-6h-1h1.6z");
}

</style>
