<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfgp2rb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vinyl-fill-sharp" /></template>
<style>
.cfgp2rb6m {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M5 12a1 1 0 0 0 2 0c0-1.331.52-2.597 1.464-3.536a5 5 0 0 1 1.59-1.071A4.9 4.9 0 0 1 12 7a1 1 0 0 0 0-2a6.9 6.9 0 0 0-2.725.551A6.9 6.9 0 0 0 7.05 7.05A6.97 6.97 0 0 0 5 12m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m7.449 2.725A6.9 6.9 0 0 0 19 12a1 1 0 0 0-2 0a4.9 4.9 0 0 1-.393 1.946a5 5 0 0 1-1.071 1.59a5 5 0 0 1-1.59 1.071A4.9 4.9 0 0 1 12 17a1 1 0 0 0 0 2a6.9 6.9 0 0 0 2.725-.551a6.9 6.9 0 0 0 2.225-1.499a6.9 6.9 0 0 0 1.499-2.225");
}

</style>
