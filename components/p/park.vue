<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sudjambsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:park" /></template>
<style>
.sudjambsc {
  fill: currentColor;
  d: path("M12.989 21H11.01v-4H4.885l4-6H6.922L12 3.73L17.077 11h-1.961l4 6h-6.127z");
}

</style>
