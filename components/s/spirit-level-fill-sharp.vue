<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq_vs1bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spirit-level-fill-sharp" /></template>
<style>
.hq_vs1bix {
  fill: currentColor;
  d: path("M2 7a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm6 3a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm8 0v4a1 1 0 0 0 2 0v-4a1 1 0 0 0-2 0m-5 4h2a2 2 0 1 0 0-4h-2a2 2 0 1 0 0 4");
}

</style>
