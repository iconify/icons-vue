<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa_8ucblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-attachment" /></template>
<style>
.xa_8ucblw {
  fill: currentColor;
  d: path("M18.5 16H7c-2.21 0-4-1.79-4-4s1.79-4 4-4h12.5a2.5 2.5 0 0 1 0 5H9c-.55 0-1-.45-1-1s.45-1 1-1h9.5V9.5H9a2.5 2.5 0 0 0 0 5h10.5c2.21 0 4-1.79 4-4s-1.79-4-4-4H7c-3.04 0-5.5 2.46-5.5 5.5s2.46 5.5 5.5 5.5h11.5z");
}

</style>
