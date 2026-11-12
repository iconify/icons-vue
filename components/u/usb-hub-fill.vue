<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh-epdywk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-hub-fill" /></template>
<style>
.dh-epdywk {
  fill: currentColor;
  d: path("M10 2h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-1v4h6a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h6V8h-1a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2M7 16a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Zm8 0a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Z");
}

</style>
