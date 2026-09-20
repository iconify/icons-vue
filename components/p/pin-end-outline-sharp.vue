<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqvj3mb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-end-outline-sharp" /></template>
<style>
.aqvj3mb-n {
  fill: currentColor;
  d: path("M2 20V4h20v8h-2V6H4v12h10v2zm11.95-5.625L11 11.425v2.225H9V8h5.65v2H12.4l2.95 2.95zM19 20q-1.25 0-2.125-.875T16 17t.875-2.125T19 14t2.125.875T22 17t-.875 2.125T19 20");
}

</style>
