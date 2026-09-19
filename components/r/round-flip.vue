<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rknk9vbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-flip" /></template>
<style>
.rknk9vbeq {
  fill: currentColor;
  d: path("M15 21h2v-2h-2zm4-12h2V7h-2zM3 5v14c0 1.1.9 2 2 2h3c.55 0 1-.45 1-1s-.45-1-1-1H6c-.55 0-1-.45-1-1V6c0-.55.45-1 1-1h2c.55 0 1-.45 1-1s-.45-1-1-1H5c-1.1 0-2 .9-2 2m16-2v2h2c0-1.1-.9-2-2-2m-7 20c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1v20c0 .55.45 1 1 1m7-6h2v-2h-2zM15 5h2V3h-2zm4 8h2v-2h-2zm0 8c1.1 0 2-.9 2-2h-2z");
}

</style>
