<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w46k0be2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-bookmark-remove" /></template>
<style>
.w46k0be2b {
  fill: currentColor;
  d: path("M21 6c0 .55-.45 1-1 1h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1m-2 4.9A5.002 5.002 0 0 1 14 3H7c-1.1 0-2 .9-2 2v14.48c0 .72.73 1.2 1.39.92L12 18l5.61 2.4c.66.28 1.39-.2 1.39-.92z");
}

</style>
