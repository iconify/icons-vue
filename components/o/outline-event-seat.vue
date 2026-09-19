<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soan-li2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-event-seat" /></template>
<style>
.soan-li2s {
  fill: currentColor;
  d: path("M15 5v7H9V5zm0-2H9c-1.1 0-2 .9-2 2v9h10V5c0-1.1-.9-2-2-2m7 7h-3v3h3zM5 10H2v3h3zm15 5H4v6h2v-4h12v4h2z");
}

</style>
