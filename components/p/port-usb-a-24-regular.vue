<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5c6n6fwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-a-24-regular" /></template>
<style>
.v5c6n6fwu {
  fill: currentColor;
  d: path("M18 8H6a2.006 2.006 0 0 0-2 2v4a2.006 2.006 0 0 0 2 2h12a2.006 2.006 0 0 0 2-2v-4a2.006 2.006 0 0 0-2-2M5.5 10a.495.495 0 0 1 .5-.5h12a.495.495 0 0 1 .5.5v2h-13z");
}

</style>
