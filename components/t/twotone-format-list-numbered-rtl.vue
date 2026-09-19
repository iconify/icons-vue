<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo3dloltf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-list-numbered-rtl" /></template>
<style>
.fo3dloltf {
  fill: currentColor;
  d: path("M2 11h14v2H2zm16 6h2v.5h-1v1h1v.5h-2v1h3v-4h-3zm0-6h1.8L18 13.1v.9h3v-1h-1.8l1.8-2.1V10h-3zm2-3V4h-2v1h1v3zM2 17h14v2H2zM2 5h14v2H2z");
}

</style>
