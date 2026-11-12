<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2m0k2e_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-warning-corner-fill-sharp" /></template>
<style>
.c2m0k2e_n {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1ZM7.01 6H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M10 14v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1m8 0v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m10 4a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
