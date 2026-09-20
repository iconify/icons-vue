<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v26v-qbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tv-usb-24-regular" /></template>
<style>
.v26v-qbpo {
  fill: currentColor;
  d: path("M4.75 3A2.75 2.75 0 0 0 2 5.75v8.5A2.75 2.75 0 0 0 4.75 17h9.75v-1.5H4.75c-.69 0-1.25-.56-1.25-1.25v-8.5c0-.69.56-1.25 1.25-1.25h14.5c.69 0 1.25.56 1.25 1.25V8.5h.5c.356 0 .694.074 1 .208V5.75A2.75 2.75 0 0 0 19.25 3zm1 15.5h9.001q.069.143.157.276l.8 1.224H5.75a.75.75 0 0 1 0-1.5M17.5 20l-1.337-2.045a1 1 0 0 1-.163-.547V14a1 1 0 0 1 1-1v-2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v2a1 1 0 0 1 1 1v3.44a1 1 0 0 1-.167.554L21.5 20v2a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1zm3-8.5h-2V13h2z");
}

</style>
