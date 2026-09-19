<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3h_59kbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signpost" /></template>
<style>
.p3h_59kbb {
  fill: currentColor;
  d: path("M13 10h5l3-3l-3-3h-5V2h-2v2H4v6h7v2H6l-3 3l3 3h5v4h2v-4h7v-6h-7z");
}

</style>
