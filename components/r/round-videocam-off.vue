<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me8uq9ajd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-videocam-off" /></template>
<style>
.me8uq9ajd {
  fill: currentColor;
  d: path("M21 14.2V8.91c0-.89-1.08-1.34-1.71-.71L17 10.5V7c0-.55-.45-1-1-1h-5.61l8.91 8.91c.62.63 1.7.18 1.7-.71M2.71 2.56a.996.996 0 0 0 0 1.41L4.73 6H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.21 0 .39-.08.55-.18l2.48 2.48a.996.996 0 1 0 1.41-1.41L4.12 2.56a.996.996 0 0 0-1.41 0");
}

</style>
