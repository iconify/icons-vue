<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qc1zjob1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-off-16-regular" /></template>
<style>
.qc1zjob1g {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .707 0l13 13a.5.5 0 1 1-.707.707L8.784 9.491a1 1 0 0 0-.284.698v1.898a1.5 1.5 0 1 1-1.006.002a1 1 0 0 0-.344-.659L4.698 9.328A2 2 0 0 1 4 7.81v-.945a1 1 0 0 1 .31-1.848L1.146 1.853a.5.5 0 0 1 0-.707m4.333 5.04a1 1 0 0 1-.48.679v.945c.001.292.13.57.35.759l2.15 1.844V8.207zM12 3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5v.81c0 .584-.255 1.138-.697 1.518l-.998.854l-.71-.709l1.056-.904a1 1 0 0 0 .35-.759V5a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 11 3zM7.602 1.2a.5.5 0 0 1 .8 0l.748.998a.5.5 0 0 1-.4.8H8.5v3.38l-1-1v-2.38h-.248a.501.501 0 0 1-.4-.8z");
}

</style>
