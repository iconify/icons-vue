<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="pywz1og7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-row-28-regular" /></template>
<style>
.pywz1og7i {
  fill: currentColor;
  d: path("M3.75 23.5a.75.75 0 0 0 0 1.5h20.5a.75.75 0 0 0 0-1.5zm0-20.5a.75.75 0 0 0 0 1.5h20.5a.75.75 0 0 0 0-1.5zM3 16.25A2.75 2.75 0 0 0 5.75 19h16.5A2.75 2.75 0 0 0 25 16.25v-4.5A2.75 2.75 0 0 0 22.25 9H5.75A2.75 2.75 0 0 0 3 11.75zm2.75 1.25c-.69 0-1.25-.56-1.25-1.25v-4.5c0-.69.56-1.25 1.25-1.25H10v7zm5.75 0v-7h5v7zm6.5 0v-7h4.25c.69 0 1.25.56 1.25 1.25v4.5c0 .69-.56 1.25-1.25 1.25z");
}

</style>
