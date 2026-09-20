<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="arn148vlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:preview-link-28-regular" /></template>
<style>
.arn148vlp {
  fill: currentColor;
  d: path("M22.251 4a3.75 3.75 0 0 1 3.75 3.75v12.5a3.75 3.75 0 0 1-3.75 3.75H5.754a3.75 3.75 0 0 1-3.75-3.75V7.75A3.75 3.75 0 0 1 5.754 4zM5.754 5.5a2.25 2.25 0 0 0-2.25 2.25v12.5a2.25 2.25 0 0 0 2.25 2.25H22.25a2.25 2.25 0 0 0 2.25-2.25V7.75a2.25 2.25 0 0 0-2.25-2.25zm6.996 14a.75.75 0 0 1 0 1.5H5.754a.75.75 0 0 1 0-1.5zm9.001-3c.69 0 1.25.56 1.25 1.25v2c0 .69-.56 1.25-1.25 1.25h-5.497c-.69 0-1.25-.56-1.25-1.25v-2c0-.69.56-1.25 1.25-1.25zm-5.247 3H21.5V18h-4.997zm-3.754-3a.75.75 0 0 1 0 1.5H5.754a.75.75 0 0 1 0-1.5zM21.751 7c.69 0 1.25.56 1.25 1.25v5.5c0 .69-.56 1.25-1.25 1.25H6.254c-.69 0-1.25-.56-1.25-1.25v-5.5c0-.69.56-1.25 1.25-1.25zM6.504 13.5H21.5v-5H6.504z");
}

</style>
