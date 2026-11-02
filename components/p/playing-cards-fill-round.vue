<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq89u5v2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-fill-round" /></template>
<style>
.fq89u5v2u {
  fill: currentColor;
  d: path("M8 2h8a5 5 0 0 1 5 5v10a1 1 0 0 1-2 0V7a3 3 0 0 0-3-3H8a1 1 0 0 1 0-2m-5 9a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Zm9.832 2.445l-2-3a1 1 0 0 0-1.664 0l-2 3a1 1 0 0 0 0 1.11l2 3a1 1 0 0 0 1.664 0l2-3a1 1 0 0 0 0-1.11");
}

</style>
