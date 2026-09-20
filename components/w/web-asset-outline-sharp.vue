<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr9gnfb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:web-asset-outline-sharp" /></template>
<style>
.gr9gnfb0h {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V8H4z");
}

</style>
