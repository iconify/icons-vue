<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrzow-tyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:two-pager-sharp" /></template>
<style>
.mrzow-tyc {
  fill: currentColor;
  d: path("M3 19V5h18v14zm9.5-1H20V6h-7.5zm-7.115-2.5h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm8.5 6h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm0-3h4.73v-1h-4.73z");
}

</style>
