<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq_bt8b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-ad-off-sharp" /></template>
<style>
.pq_bt8b2w {
  fill: currentColor;
  d: path("m20.45 23.3l-3.3-3.3H2V4h2l2 2H3.15L.65 3.5l1.425-1.425l19.8 19.8zM5 17h9.15l-2-2H5zm0-4h5.15l-2-2H5zm0-4h1.15l-2-2H5zm1.85-5H22v15.15L15.85 13H19v-2h-5.15l-2-2H15V7H9.85z");
}

</style>
