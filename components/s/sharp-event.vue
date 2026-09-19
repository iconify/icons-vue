<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zisgoccru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-event" /></template>
<style>
.zisgoccru {
  fill: currentColor;
  d: path("M17 13h-5v5h5zM16 2v2H8V2H6v2H3.01L3 22h18V4h-3V2zm3 18H5V9h14z");
}

</style>
