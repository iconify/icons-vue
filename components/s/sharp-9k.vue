<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu99nwbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-9k" /></template>
<style>
.xu99nwbdw {
  fill: currentColor;
  d: path("M8 10h1.5v1.5H8zm13-7H3v18h18zM11 9v6H6.5v-1.5h3v-1h-3V9zm7 6h-1.75l-1.75-2.25V15H13V9h1.5v2.25L16.25 9H18l-2.25 3z");
}

</style>
