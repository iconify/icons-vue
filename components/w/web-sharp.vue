<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-yaqpbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:web-sharp" /></template>
<style>
.i-yaqpbgi {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h10.5v-3.5H4zm12.5 0H20V9h-3.5zM4 12.5h10.5V9H4z");
}

</style>
