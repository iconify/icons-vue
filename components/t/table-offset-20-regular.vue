<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a2hdyqbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-offset-20-regular" /></template>
<style>
.a2hdyqbeb {
  fill: currentColor;
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5v9A2.5 2.5 0 0 0 5.5 17h9a2.5 2.5 0 0 0 2.5-2.5v-9A2.5 2.5 0 0 0 14.5 3zM16 12H8V8h8zm-3 1h3v1.5a1.5 1.5 0 0 1-1.5 1.5H13zm-1 0v3H5.5A1.5 1.5 0 0 1 4 14.5V13zm-8-1V8h3v4zm0-5V5.5A1.5 1.5 0 0 1 5.5 4H12v3zm12-1.5V7h-3V4h1.5A1.5 1.5 0 0 1 16 5.5");
}

</style>
