<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5xvid--c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pages" /></template>
<style>
.l5xvid--c {
  fill: currentColor;
  d: path("M3 3v8h5L7 7l4 1V3zm5 10H3v8h8v-5l-4 1zm9 4l-4-1v5h8v-8h-5zm4-14h-8v5l4-1l-1 4h5z");
}

</style>
