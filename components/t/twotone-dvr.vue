<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnt9lebcx"/><path class="cnr1hqbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dvr" /></template>
<style>
.cnr1hqbau {
  fill: currentColor;
  d: path("M8 12h11v2H8zm0-4h11v2H8zm13-5H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h5v2h8v-2h5c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 14H3V5h18zM5 12h2v2H5zm0-4h2v2H5z");
}

.fnt9lebcx {
  fill: currentColor;
  d: path("M3 17h18V5H3zm5-9h11v2H8zm0 4h11v2H8zM5 8h2v2H5zm0 4h2v2H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
