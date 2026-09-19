<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewoqmb5xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:text-format" /></template>
<style>
.ewoqmb5xl {
  fill: currentColor;
  d: path("M5 17v2h14v-2zm4.5-4.2h5l.9 2.2h2.1L12.75 4h-1.5L6.5 15h2.1zM12 5.98L13.87 11h-3.74z");
}

</style>
