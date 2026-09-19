<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irdt5d7jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-4g-mobiledata" /></template>
<style>
.irdt5d7jg {
  fill: currentColor;
  d: path("M8 7c-.55 0-1 .45-1 1v4H5V8c0-.55-.45-1-1-1s-1 .45-1 1v5c0 .55.45 1 1 1h3v2c0 .55.45 1 1 1s1-.45 1-1v-2h1c.55 0 1-.45 1-1s-.45-1-1-1H9V8c0-.55-.45-1-1-1m9 5c0 .55.45 1 1 1h1v2h-5V9h6c.55 0 1-.45 1-1s-.45-1-1-1h-6c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h5c1.1 0 2-.9 2-2v-3c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1");
}

</style>
