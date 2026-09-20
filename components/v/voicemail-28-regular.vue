<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="acsx7yb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:voicemail-28-regular" /></template>
<style>
.acsx7yb_u {
  fill: currentColor;
  d: path("M12.373 12h3.254a3.5 3.5 0 1 0 2.873-1.5h-9a3.5 3.5 0 1 0 2.873 1.5m4.127 2a2 2 0 1 1 4 0a2 2 0 0 1-4 0m-9 0a2 2 0 1 1 4 0a2 2 0 0 1-4 0M4.754 4a2.75 2.75 0 0 0-2.75 2.75v14.5A2.75 2.75 0 0 0 4.754 24H23.25A2.75 2.75 0 0 0 26 21.25V6.75A2.75 2.75 0 0 0 23.25 4zm-1.25 2.75c0-.69.56-1.25 1.25-1.25H23.25c.69 0 1.25.56 1.25 1.25v14.5c0 .69-.56 1.25-1.25 1.25H4.755c-.69 0-1.25-.56-1.25-1.25z");
}

</style>
