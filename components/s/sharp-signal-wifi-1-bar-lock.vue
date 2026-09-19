<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv-_gnbal"/><path class="dwoou_bit"/><path class="ibm2bjbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-signal-wifi-1-bar-lock" /></template>
<style>
.dwoou_bit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M15.5 14.5c0-2.8 2.2-5 5-5c.36 0 .71.04 1.05.11L23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7L12 21.5l3.5-4.36z");
}

.ibm2bjbsg {
  fill: currentColor;
  d: path("M15.5 14.5c0-.23.04-.46.07-.68c-.92-.43-2.14-.82-3.57-.82c-3 0-5.1 1.7-5.3 1.9l5.3 6.6l3.5-4.36z");
}

.jv-_gnbal {
  fill: currentColor;
  d: path("M23 16v-1.34c0-1.47-1.2-2.75-2.66-2.66A2.484 2.484 0 0 0 18 14.5V16h-1v6h7v-6zm-1 0h-3v-1.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5z");
}

</style>
