<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z4-nbkx_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-12-regular" /></template>
<style>
.z4-nbkx_b {
  fill: currentColor;
  d: path("M2 6a4 4 0 1 1 8 0c0 1.045-.599 1.473-1.027 1.496a.76.76 0 0 1-.625-.28C8.164 7 8 6.618 8 6V4a.5.5 0 0 0-.994-.078A2.07 2.07 0 0 0 5.75 3.5C4.447 3.5 3.5 4.684 3.5 6s.947 2.5 2.25 2.5c.69 0 1.28-.332 1.683-.84q.073.11.156.207c.383.446.908.656 1.438.627C10.099 8.437 11 7.455 11 6a5 5 0 1 0-3.333 4.715a.5.5 0 0 0-.334-.942A4 4 0 0 1 2 6m5 0c0 .893-.62 1.5-1.25 1.5S4.5 6.893 4.5 6s.62-1.5 1.25-1.5S7 5.107 7 6");
}

</style>
