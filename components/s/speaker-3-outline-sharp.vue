<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0s-qbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-3-outline-sharp" /></template>
<style>
.zc0s-qbln {
  fill: currentColor;
  d: path("M6 19h12V4H6zm2 3v-1H4V2h16v19h-4v1zm4-10.5");
}

</style>
