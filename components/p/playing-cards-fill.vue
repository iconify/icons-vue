<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjflfbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-fill" /></template>
<style>
.gtjflfbrm {
  fill: currentColor;
  d: path("M8 2h10a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H8a1 1 0 0 1 0-2M3 9a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm9.832 4.445l-2-3a1 1 0 0 0-1.664 0l-2 3a1 1 0 0 0 0 1.11l2 3a1 1 0 0 0 1.664 0l2-3a1 1 0 0 0 0-1.11");
}

</style>
