<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwq39bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-south-west" /></template>
<style>
.rbwq39bfv {
  fill: currentColor;
  d: path("M15 18c0-.56-.45-1-1-1H8.41L19.3 6.11a.996.996 0 1 0-1.41-1.41L7 15.59V10c0-.55-.45-1-1-1s-1 .45-1 1v8c0 .55.45 1 1 1h8c.55 0 1-.45 1-1");
}

</style>
