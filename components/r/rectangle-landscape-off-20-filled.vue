<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uxg417b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-landscape-off-20-filled" /></template>
<style>
.uxg417b5h {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.87-1.87A3 3 0 0 1 15 16H5a3 3 0 0 1-3-3V7c0-1.162.661-2.168 1.627-2.666l-1.48-1.48a.5.5 0 0 1 0-.707M15 4a3 3 0 0 1 3 3v6a3 3 0 0 1-.821 2.058L6.12 4z");
}

</style>
