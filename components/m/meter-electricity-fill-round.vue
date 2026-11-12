<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8-c2ac1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-electricity-fill-round" /></template>
<style>
.b8-c2ac1f {
  fill: currentColor;
  d: path("M9 2h6a5 5 0 0 1 5 5v4h1a1 1 0 0 1 0 2h-1v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5v-4H3a1 1 0 0 1 0-2h1V7a5 5 0 0 1 5-5m4.8 6.6a1 1 0 0 0-1.6-1.2l-3 4A.999.999 0 0 0 10 13h2l-1.8 2.4a1 1 0 0 0 1.6 1.2l3-4A.999.999 0 0 0 14 11h-2Z");
}

</style>
