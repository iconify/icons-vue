<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9igppb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-left-outline-sharp" /></template>
<style>
.x9igppb4g {
  fill: currentColor;
  d: path("M14.885 19v-1H19V6h-4.115V5H20v14zM11.5 21v-2H4V5h7.5V3h1v18zM19 6v12z");
}

</style>
