<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auz4cobsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mobiledata-off" /></template>
<style>
.auz4cobsk {
  fill: currentColor;
  d: path("M16 7h3l-4-4l-4 4h3v4.17l2 2zM2.81 2.81L1.39 4.22L8 10.83v6.18l-3 .01L9 21l4-4l-3 .01v-4.18l9.78 9.78l1.41-1.42z");
}

</style>
