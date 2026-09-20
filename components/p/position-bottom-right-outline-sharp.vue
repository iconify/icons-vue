<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwkv2bcmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:position-bottom-right-outline-sharp" /></template>
<style>
.dwkv2bcmj {
  fill: currentColor;
  d: path("M9 17h9v-3H9zm-6 4V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
