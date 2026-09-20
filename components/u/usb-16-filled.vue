<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vmhe-tbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-16-filled" /></template>
<style>
.vmhe-tbvz {
  fill: currentColor;
  d: path("M7.585.722a.5.5 0 0 1 .831 0l1 1.497A.5.5 0 0 1 9 2.996h-.25v5.36l1.99-1.724a.75.75 0 0 0 .26-.566v-.567A.5.5 0 0 1 10.5 5V3.5A.5.5 0 0 1 11 3h1.5a.5.5 0 0 1 .5.5V5a.5.5 0 0 1-.5.5l-.001.566c0 .652-.284 1.273-.776 1.7l-2.714 2.352a.75.75 0 0 0-.259.567v1.517a1.5 1.5 0 1 1-1.621.077a.8.8 0 0 0-.138-.16L4.276 9.766a2.25 2.25 0 0 1-.776-1.7v-.819a1.25 1.25 0 1 1 1.5 0v.819a.75.75 0 0 0 .259.566l1.991 1.725v-7.36h-.249a.5.5 0 0 1-.416-.778z");
}

</style>
