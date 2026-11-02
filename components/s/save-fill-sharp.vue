<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khhuouisa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-fill-sharp" /></template>
<style>
.khhuouisa {
  fill: currentColor;
  d: path("M18 22v-8a1 1 0 0 0-1-1H7a1 1 0 0 0-1 1v8H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h14c.265 0 .52.105.707.293l4 4A1 1 0 0 1 22 7v14a1 1 0 0 1-1 1ZM15 6H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2M8 22v-7h8v7Z");
}

</style>
