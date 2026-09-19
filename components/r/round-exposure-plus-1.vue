<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_bk97bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-exposure-plus-1" /></template>
<style>
.e_bk97bqo {
  fill: currentColor;
  d: path("M9 7c-.55 0-1 .45-1 1v3H5c-.55 0-1 .45-1 1s.45 1 1 1h3v3c0 .55.45 1 1 1s1-.45 1-1v-3h3c.55 0 1-.45 1-1s-.45-1-1-1h-3V8c0-.55-.45-1-1-1m11 11h-2V7.38L15 8.4V6.7L19.7 5h.3z");
}

</style>
