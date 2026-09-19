<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upfb69bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sos" /></template>
<style>
.upfb69bwq {
  fill: currentColor;
  d: path("M13.5 7h-3c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h3c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2m0 8h-3V9h3zM1 15h4v-2H3c-1.1 0-2-.9-2-2V9c0-1.1.9-2 2-2h4v2H3v2h2c1.1 0 2 .9 2 2v2c0 1.1-.9 2-2 2H1zm16 0h4v-2h-2c-1.1 0-2-.9-2-2V9c0-1.1.9-2 2-2h4v2h-4v2h2c1.1 0 2 .9 2 2v2c0 1.1-.9 2-2 2h-4z");
}

</style>
