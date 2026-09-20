<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="uyg2xwbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:preview-link-28-filled" /></template>
<style>
.uyg2xwbal {
  fill: currentColor;
  d: path("M22.25 4A3.75 3.75 0 0 1 26 7.75v12.5A3.75 3.75 0 0 1 22.25 24H5.75A3.75 3.75 0 0 1 2 20.25V7.75A3.75 3.75 0 0 1 5.75 4zM5.754 19.5a.75.75 0 0 0 0 1.5h6.996a.75.75 0 0 0 0-1.5zm10.5-3c-.69 0-1.25.56-1.25 1.25v2c0 .69.56 1.25 1.25 1.25h5.497c.69 0 1.25-.56 1.25-1.25v-2c0-.69-.56-1.25-1.25-1.25zm5.247 3h-4.997V18H21.5zm-15.747-3a.75.75 0 0 0 0 1.5h6.996a.75.75 0 0 0 0-1.5zm.5-9.5c-.69 0-1.25.56-1.25 1.25v5.5c0 .69.56 1.25 1.25 1.25H21.75c.69 0 1.25-.56 1.25-1.25v-5.5C23 7.56 22.44 7 21.75 7zM21.5 13.5H6.504v-5H21.5z");
}

</style>
