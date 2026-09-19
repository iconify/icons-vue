<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6v8_f18v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-notification-important" /></template>
<style>
.v6v8_f18v {
  fill: currentColor;
  d: path("M10.01 21.01c0 1.1.89 1.99 1.99 1.99s1.99-.89 1.99-1.99zM12 6c2.76 0 5 2.24 5 5v7H7v-7c0-2.76 2.24-5 5-5m0-4.5c-.83 0-1.5.67-1.5 1.5v1.17C7.36 4.85 5 7.65 5 11v6l-2 2v1h18v-1l-2-2v-6c0-3.35-2.36-6.15-5.5-6.83V3c0-.83-.67-1.5-1.5-1.5M11 8h2v4h-2zm0 6h2v2h-2z");
}

</style>
