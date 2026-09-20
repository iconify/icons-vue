<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp1-kibcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-increase" /></template>
<style>
.rp1-kibcn {
  fill: currentColor;
  d: path("M1 19L6.25 5h2.5L14 19h-2.4l-1.275-3.575h-5.65L3.4 19zm4.4-5.6h4.2L7.55 7.6h-.1zM18 16v-3h-3v-2h3V8h2v3h3v2h-3v3z");
}

</style>
