<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceowv_bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mic-external-on-sharp" /></template>
<style>
.ceowv_bgf {
  fill: currentColor;
  d: path("M4.8 7q-.375-.425-.587-.925T4 5q0-1.25.875-2.125T7 2t2.125.875T10 5q0 .575-.213 1.075T9.2 7zM6 22v-4H5L4 8h6L9 18H8v2h4V2h8v20h-2V4h-4v18z");
}

</style>
