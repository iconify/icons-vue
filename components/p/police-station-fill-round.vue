<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="revtdpbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-fill-round" /></template>
<style>
.revtdpbuw {
  fill: currentColor;
  d: path("M15 22v-3a3 3 0 1 0-6 0v3H3a1 1 0 0 1 0-2h1V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v13h1a1 1 0 0 1 0 2ZM12.894 5.953a.998.998 0 0 0-1.788 0l-.966 1.931l-2.281.326a1.001 1.001 0 0 0-.566 1.697l1.636 1.636l-.315 1.893a1 1 0 0 0 .392.968a1 1 0 0 0 1.041.09L12 13.518l1.953.976a1 1 0 0 0 1.041-.09a1 1 0 0 0 .392-.968l-.315-1.893l1.636-1.636a1.001 1.001 0 0 0-.566-1.697l-2.281-.326ZM13 19v3h-2v-3a1 1 0 0 1 2 0");
}

</style>
