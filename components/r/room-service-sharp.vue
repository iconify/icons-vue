<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwf5mky7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:room-service-sharp" /></template>
<style>
.xwf5mky7o {
  fill: currentColor;
  d: path("M2 19v-2h20v2zm1-3v-1q0-3.2 1.963-5.65T10 6.25V4h4v2.25q3.1.65 5.05 3.1T21 15v1z");
}

</style>
