<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp1thubud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-all-out" /></template>
<style>
.wp1thubud {
  fill: currentColor;
  d: path("M4 4.5V8l4-4H4.5c-.28 0-.5.22-.5.5M16 4l4 4V4.5c0-.28-.22-.5-.5-.5zm4 15.5V16l-4 4h3.5c.28 0 .5-.22.5-.5M4.5 20H8l-4-4v3.5c0 .28.22.5.5.5M19 12c0-3.87-3.13-7-7-7s-7 3.13-7 7s3.13 7 7 7s7-3.13 7-7m-7 5c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

</style>
