<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qawt-ubmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:on-hub-device-outline-rounded" /></template>
<style>
.qawt-ubmh {
  fill: currentColor;
  d: path("M9 21q-.425 0-.712-.288T8 20t.288-.712T9 19h6q.425 0 .713.288T16 20t-.288.713T15 21zm-1.075-3.925L7 5.15q-.075-.875.525-1.513T9 3h6q.875 0 1.475.637T17 5.15l-.925 11.925q-.05.4-.325.663t-.675.262h-6.15q-.4 0-.675-.262t-.325-.663M9.85 16h4.3L15 5H9zm0-11H9h6z");
}

</style>
