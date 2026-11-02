<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tywym2n_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-descending-fill-sharp" /></template>
<style>
.tywym2n_w {
  fill: currentColor;
  d: path("M4 5h12a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m13.293 13.707l-3-3a.999.999 0 1 1 1.414-1.414L17 15.586V10a1 1 0 0 1 2 0v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0M4 10h9a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m0 5h6a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
