<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky5zau9vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-day-sharp" /></template>
<style>
.ky5zau9vn {
  fill: currentColor;
  d: path("M3 20v-2h18v2zm0-4V8h18v8zM3 6V4h18v2z");
}

</style>
