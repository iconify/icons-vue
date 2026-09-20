<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgravacfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:web-outline-sharp" /></template>
<style>
.mgravacfw {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h11v-3.884H4zm12 0h4V9.23h-4zM4 13.116h11V9.23H4z");
}

</style>
