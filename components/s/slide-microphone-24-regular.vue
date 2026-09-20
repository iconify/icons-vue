<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym94yeiiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-microphone-24-regular" /></template>
<style>
.ym94yeiiv {
  fill: currentColor;
  d: path("M22.25 16a.75.75 0 0 1 .75.75a4.75 4.75 0 0 1-4 4.69v.81a.75.75 0 0 1-1.5 0v-.81a4.75 4.75 0 0 1-4-4.69a.75.75 0 0 1 1.5 0a3.25 3.25 0 0 0 6.5 0a.75.75 0 0 1 .75-.75m-3-12A2.75 2.75 0 0 1 22 6.75v8.27a1.8 1.8 0 0 0-.5.15v-.92c0-.92-.385-1.75-1-2.342V6.75c0-.69-.56-1.25-1.25-1.25H4.75c-.69 0-1.25.56-1.25 1.25v10.5c0 .69.56 1.25 1.25 1.25h8.023c.172.539.42 1.043.733 1.5H4.75A2.75 2.75 0 0 1 2 17.25V6.75A2.75 2.75 0 0 1 4.75 4zm-1 8a2.25 2.25 0 0 1 2.25 2.25v2.5a2.25 2.25 0 0 1-4.5 0v-2.5A2.25 2.25 0 0 1 18.25 12m-6 2a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5zm2-3a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm-3-3a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5z");
}

</style>
