<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k88m_ab5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pages-outline-sharp" /></template>
<style>
.k88m_ab5c {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zM5 5v14zm4.075 11.25L12 14.475l2.925 1.775l-.775-3.325l2.6-2.25l-3.425-.275L12 7.25l-1.325 3.15l-3.425.275l2.6 2.25z");
}

</style>
