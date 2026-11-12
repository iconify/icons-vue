<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4qdg3fzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:textarea-fill" /></template>
<style>
.y4qdg3fzx {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m11 3H6a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2m-6 4H6a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2m8.293 3.293l-6 6a.999.999 0 1 0 1.414 1.414l6-6a.999.999 0 1 0-1.414-1.414M18.001 20a1 1 0 0 0 .706-.293l1-1a1 1 0 0 0 .293-.706v-.002a1 1 0 0 0-1.707-.706l-1 1A.998.998 0 0 0 17.999 20Z");
}

</style>
