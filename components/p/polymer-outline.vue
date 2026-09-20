<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukf8gbpkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:polymer-outline" /></template>
<style>
.ukf8gbpkc {
  fill: currentColor;
  d: path("M4.95 20L.5 12L5 4h4l-4.5 8l2.6 4.65L14.9 4H19l4.5 8l-4.5 8h-4l4.5-8l-2.6-4.6L9.15 20z");
}

</style>
