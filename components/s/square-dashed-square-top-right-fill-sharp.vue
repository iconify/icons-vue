<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayxjrmbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-fill-sharp" /></template>
<style>
.ayxjrmbqd {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0Zm7 11V3a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1m-7-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Zm1 12a1 1 0 0 1-1-1v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2Zm19-1a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Zm-12 1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2Z");
}

</style>
