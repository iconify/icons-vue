<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zw0j47r6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mobile-optimized-20-regular" /></template>
<style>
.zw0j47r6t {
  fill: currentColor;
  d: path("M5 2.5a.5.5 0 0 0-1 0V4H2.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5zm11 0a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H16zM7 5a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1zm0 1h6v8H7zM4.5 18a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 0 0 1H4v1.5a.5.5 0 0 0 .5.5m11 0a.5.5 0 0 0 .5-.5V16h1.5a.5.5 0 0 0 0-1h-2a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5m-7-10a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm0 2a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
}

</style>
