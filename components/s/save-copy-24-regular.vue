<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoydg8b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-copy-24-regular" /></template>
<style>
.qoydg8b8y {
  fill: currentColor;
  d: path("M3.504 5.627A2.25 2.25 0 0 0 2 7.75v10A4.25 4.25 0 0 0 6.25 22h10a2.25 2.25 0 0 0 2.123-1.504l-2.097.004H6.25a2.75 2.75 0 0 1-2.75-2.75v-10l.004-.051zM6.754 2a2.25 2.25 0 0 0-2.25 2.25v12.997a2.25 2.25 0 0 0 2.25 2.25H19.75a2.25 2.25 0 0 0 2.25-2.25V4.25A2.25 2.25 0 0 0 19.75 2zm0 1.5H19.75a.75.75 0 0 1 .75.75v12.997a.75.75 0 0 1-.75.75H6.753a.75.75 0 0 1-.75-.75V4.25a.75.75 0 0 1 .75-.75m6.496 3.25a.75.75 0 0 0-.75.75V10H10a.75.75 0 0 0 0 1.5h2.5V14a.75.75 0 0 0 1.5 0v-2.5h2.5a.75.75 0 0 0 0-1.5H14V7.5a.75.75 0 0 0-.75-.75");
}

</style>
