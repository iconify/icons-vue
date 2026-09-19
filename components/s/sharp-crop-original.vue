<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhu3uvbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-original" /></template>
<style>
.rhu3uvbis {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-2 16H5V5h14zm-5.04-6.71l-2.75 3.54l-1.96-2.36L6.5 17h11z");
}

</style>
