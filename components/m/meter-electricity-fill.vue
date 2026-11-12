<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmofhe2dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-electricity-fill" /></template>
<style>
.hmofhe2dp {
  fill: currentColor;
  d: path("M7 2h10a3 3 0 0 1 3 3v6h1a1 1 0 0 1 0 2h-1v6a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-6H3a1 1 0 0 1 0-2h1V5a3 3 0 0 1 3-3m6.8 6.6a1 1 0 0 0-1.6-1.2l-3 4A.999.999 0 0 0 10 13h2l-1.8 2.4a1 1 0 0 0 1.6 1.2l3-4A.999.999 0 0 0 14 11h-2Z");
}

</style>
