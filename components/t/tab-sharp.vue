<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5mnlg7fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-sharp" /></template>
<style>
.h5mnlg7fd {
  fill: currentColor;
  d: path("M3 19V5h18v14zm10-9h7V6h-7z");
}

</style>
