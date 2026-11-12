<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czy1fj-es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-fill" /></template>
<style>
.czy1fj-es {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m2.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 17a2 2 0 0 1 2-2a3 3 0 1 1 6 0a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Zm-3 4H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m7-6h2a1 1 0 0 0-2 0m-8.99 1H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M20 17h-6v3h6Z");
}

</style>
