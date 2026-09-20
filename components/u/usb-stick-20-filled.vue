<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c4di70bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-stick-20-filled" /></template>
<style>
.c4di70bgd {
  fill: currentColor;
  d: path("M7 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5V6a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2zM8 6h4V3H8z");
}

</style>
