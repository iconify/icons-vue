<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbq5eb1sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-format-overline" /></template>
<style>
.gbq5eb1sx {
  fill: currentColor;
  d: path("M5 4c0-.55.45-1 1-1h12c.55 0 1 .45 1 1s-.45 1-1 1H6c-.55 0-1-.45-1-1m7 3c-3.87 0-7 3.13-7 7s3.13 7 7 7s7-3.13 7-7s-3.13-7-7-7m0 11.5c-2.49 0-4.5-2.01-4.5-4.5S9.51 9.5 12 9.5s4.5 2.01 4.5 4.5s-2.01 4.5-4.5 4.5");
}

</style>
