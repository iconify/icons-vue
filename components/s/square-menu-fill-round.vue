<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-hs4siur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-menu-fill-round" /></template>
<style>
.g-hs4siur {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm14 0H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m0 4H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-8 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Z");
}

</style>
