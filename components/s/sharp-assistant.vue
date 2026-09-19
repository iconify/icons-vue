<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsz1prsax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-assistant" /></template>
<style>
.dsz1prsax {
  fill: currentColor;
  d: path("M21 2H3v18h6l3 3l3-3h6zm-7.12 10.88L12 17l-1.88-4.12L6 11l4.12-1.88L12 5l1.88 4.12L18 11z");
}

</style>
