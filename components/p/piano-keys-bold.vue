<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o3wdceb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:piano-keys-bold" /></template>
<style>
.o3wdceb0k {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20M92 132V52h24v80Zm52 24v48h-32v-48Zm20-24h-24V52h24ZM52 52h16v92a12 12 0 0 0 12 12h8v48H52Zm152 152h-36v-48h8a12 12 0 0 0 12-12V52h16Z");
}

</style>
