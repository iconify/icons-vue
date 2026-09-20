<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr50cz-on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reset-tv-sharp" /></template>
<style>
.lr50cz-on {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v7h-9.2l1.85-1.85l-1.4-1.4L9 11l4.25 4.25l1.4-1.4L12.8 12H22v7h-6v2z");
}

</style>
