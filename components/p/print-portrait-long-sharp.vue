<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebo8zzb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-long-sharp" /></template>
<style>
.ebo8zzb9h {
  fill: currentColor;
  d: path("M5 9.77V7.845h.923V4.681L6.773 4l6.593 2.217v14.26l-.812.546l-6.631-2.294V16.23H5v-1.923h.923V9.769zM14.385 19V5.352L10.475 4H18v15z");
}

</style>
