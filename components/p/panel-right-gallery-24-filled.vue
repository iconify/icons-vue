<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt7wgu7fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-gallery-24-filled" /></template>
<style>
.pt7wgu7fi {
  fill: currentColor;
  d: path("M18.75 4A3.25 3.25 0 0 1 22 7.25V8.5h-6v-3H5.25A1.75 1.75 0 0 0 3.5 7.25v9.5c0 .966.784 1.75 1.75 1.75H16v-3h6v1.25A3.25 3.25 0 0 1 18.75 20H5.25A3.25 3.25 0 0 1 2 16.75v-9.5A3.25 3.25 0 0 1 5.25 4zM22 14v-4h-6v4z");
}

</style>
