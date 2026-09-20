<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prh1y1ktb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-stick-20-regular" /></template>
<style>
.prh1y1ktb {
  fill: currentColor;
  d: path("M7.5 2h5a.5.5 0 0 1 .5.5V6a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2V2.5a.5.5 0 0 1 .5-.5M12 6V3H8v3zM7 7a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1z");
}

</style>
