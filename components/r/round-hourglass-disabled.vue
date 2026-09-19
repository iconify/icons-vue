<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypes36bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-hourglass-disabled" /></template>
<style>
.ypes36bmc {
  fill: currentColor;
  d: path("M2.81 2.81a.996.996 0 0 0-1.41 0C1 3.2 1 3.83 1.39 4.22l8.19 8.19l-3 3.01c-.37.38-.58.89-.58 1.42V20c0 1.1.9 2 2 2h8c.86 0 1.58-.54 1.87-1.3l1.91 1.91a.996.996 0 1 0 1.41-1.41zM16 19c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1v-2.5l2.84-2.84L16 18.83zM8 5c0-.55.45-1 1-1h6c.55 0 1 .45 1 1v2.5l-2.84 2.84l1.25 1.25l3-2.99c.38-.38.59-.89.59-1.42V4a2 2 0 0 0-2-2H8c-.86 0-1.58.54-1.87 1.3L8 5.17z");
}

</style>
