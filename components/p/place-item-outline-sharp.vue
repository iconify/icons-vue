<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snecruorz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:place-item-outline-sharp" /></template>
<style>
.snecruorz {
  fill: currentColor;
  d: path("M3 21V7h6v2H5v10h14V9h-4V7h6v14zm9-5l-4-4l1.4-1.4l1.6 1.575V0h2v12.175l1.6-1.575L16 12z");
}

</style>
