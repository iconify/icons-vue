<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ouc-fgxna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-c-20-filled" /></template>
<style>
.ouc-fgxna {
  fill: currentColor;
  d: path("M4.5 10a2 2 0 0 1 2-2h7a2 2 0 1 1 0 4h-7a2 2 0 0 1-2-2");
}

</style>
