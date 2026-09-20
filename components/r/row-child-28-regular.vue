<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xpzh20btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:row-child-28-regular" /></template>
<style>
.xpzh20btc {
  fill: currentColor;
  d: path("M3 5.75A2.75 2.75 0 0 1 5.75 3h16.5A2.75 2.75 0 0 1 25 5.75v4a2.75 2.75 0 0 1-2.75 2.75H8.5v4.75a2.25 2.25 0 0 0 2.25 2.25H14v-1.25a2.75 2.75 0 0 1 2.75-2.75h5.5A2.75 2.75 0 0 1 25 18.25v4A2.75 2.75 0 0 1 22.25 25h-5.5A2.75 2.75 0 0 1 14 22.25V21h-3.25A3.75 3.75 0 0 1 7 17.25V12.5H5.75A2.75 2.75 0 0 1 3 9.75zM22.25 11c.69 0 1.25-.56 1.25-1.25v-4c0-.69-.56-1.25-1.25-1.25H5.75c-.69 0-1.25.56-1.25 1.25v4c0 .69.56 1.25 1.25 1.25zm-6.75 7.25v4c0 .69.56 1.25 1.25 1.25h5.5c.69 0 1.25-.56 1.25-1.25v-4c0-.69-.56-1.25-1.25-1.25h-5.5c-.69 0-1.25.56-1.25 1.25");
}

</style>
