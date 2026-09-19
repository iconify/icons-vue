<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lng28lb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-swipe-down" /></template>
<style>
.lng28lb9v {
  fill: currentColor;
  d: path("M3.8 12.18c-.2-.86-.3-1.76-.3-2.68c0-2.84.99-5.45 2.63-7.5L7.2 3.07a10.46 10.46 0 0 0-1.88 8.99l1.62-1.62L8 11.5L4.5 15L1 11.5l1.06-1.06zm17.91-1l2.09 7.39l-8.23 3.65l-6.84-2.85l.61-1.62l3.8-.75l-4.35-9.83c-.34-.76 0-1.64.76-1.98s1.64 0 1.98.76l2.43 5.49l1.26-.56z");
}

</style>
