<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx4yu4oux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-auto-awesome-motion" /></template>
<style>
.dx4yu4oux {
  fill: currentColor;
  d: path("M13 2H4c-1.1 0-2 .9-2 2v9c0 .55.45 1 1 1s1-.45 1-1V4h9c.55 0 1-.45 1-1s-.45-1-1-1m4 4H8c-1.1 0-2 .9-2 2v9c0 .55.45 1 1 1s1-.45 1-1V8h9c.55 0 1-.45 1-1s-.45-1-1-1m3 4h-8c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-8c0-1.1-.9-2-2-2");
}

</style>
