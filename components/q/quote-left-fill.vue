<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svphg468e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-left-fill" /></template>
<style>
.svphg468e {
  fill: currentColor;
  d: path("M3 11c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 8 6a1 1 0 0 1 0 2c-1.27 0-2.405.804-2.83 2H8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm2 1v3a1 1 0 0 0 1 1h2a.997.997 0 0 0 1-1v-2a.997.997 0 0 0-1-1Zm8-1c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 18 6a1 1 0 0 1 0 2c-1.27 0-2.405.804-2.83 2H18a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Zm2 1v3a.997.997 0 0 0 1 1h2a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1Z");
}

</style>
