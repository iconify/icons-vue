<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xxob3urgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-16-regular" /></template>
<style>
.xxob3urgk {
  fill: currentColor;
  d: path("M7.6 1.2a.5.5 0 0 1 .8 0l.75.998a.5.5 0 0 1-.401.8H8.5v5.415l2.15-1.844A1 1 0 0 0 11 5.81V5a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 11 3h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5v.81a2 2 0 0 1-.698 1.518L8.85 9.43a1 1 0 0 0-.35.76v1.897a1.5 1.5 0 1 1-1.006.002a1 1 0 0 0-.344-.659L4.698 9.329A2 2 0 0 1 4 7.81v-.945a.999.999 0 1 1 1 0v.945a1 1 0 0 0 .35.76l2.15 1.843V2.999h-.249a.5.5 0 0 1-.4-.801z");
}

</style>
