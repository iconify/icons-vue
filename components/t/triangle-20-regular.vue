<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qls_vibnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-20-regular" /></template>
<style>
.qls_vibnt {
  fill: currentColor;
  d: path("M2.502 18a1.5 1.5 0 0 1-1.326-2.2l7.395-14C9.13.74 10.644.731 11.216 1.783l7.6 14.002A1.5 1.5 0 0 1 17.497 18zm-.442-1.733a.5.5 0 0 0 .442.733h14.995a.5.5 0 0 0 .44-.738l-7.6-14.001a.5.5 0 0 0-.882.005z");
}

</style>
