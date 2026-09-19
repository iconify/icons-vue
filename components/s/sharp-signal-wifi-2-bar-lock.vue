<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja0pv6b-f"/><path class="dwoou_bit"/><path class="zj28nxbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-signal-wifi-2-bar-lock" /></template>
<style>
.dwoou_bit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M15.5 14.5c0-2.8 2.2-5 5-5c.36 0 .71.04 1.05.11L23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7L12 21.5l3.5-4.36z");
}

.ja0pv6b-f {
  fill: currentColor;
  d: path("M23 16v-1.5c0-1.4-1.1-2.5-2.5-2.5S18 13.1 18 14.5V16h-1v6h7v-6zm-1 0h-3v-1.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5z");
}

.zj28nxbix {
  fill: currentColor;
  d: path("M15.5 14.5c0-1.34.51-2.53 1.34-3.42C15.62 10.51 13.98 10 12 10c-4.1 0-6.8 2.2-7.2 2.5l7.2 9l3.5-4.38z");
}

</style>
