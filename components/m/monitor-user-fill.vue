<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry4sh0yox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-user-fill" /></template>
<style>
.ry4sh0yox {
  fill: currentColor;
  d: path("M6 3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m3 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 7h6a1 1 0 0 0 1-1c0-.257-.075-.506-.209-.725C15.124 13.188 13.099 13 12 13s-3.124.188-3.791 1.275A1.4 1.4 0 0 0 8 15a1 1 0 0 0 1 1m0 3h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
