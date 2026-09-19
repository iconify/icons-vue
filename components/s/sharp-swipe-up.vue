<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inx6avbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-swipe-up" /></template>
<style>
.inx6avbkp {
  fill: currentColor;
  d: path("M2.06 5.56L1 4.5L4.5 1L8 4.5L6.94 5.56L5.32 3.94a10.46 10.46 0 0 0 1.88 8.99L6.13 14A11.97 11.97 0 0 1 3.5 6.5c0-.92.1-1.82.3-2.68zm19.65 5.62l2.09 7.39l-8.23 3.65l-6.84-2.85l.61-1.62l3.8-.75l-4.35-9.83c-.34-.76 0-1.64.76-1.98s1.64 0 1.98.76l2.43 5.49l1.26-.56z");
}

</style>
