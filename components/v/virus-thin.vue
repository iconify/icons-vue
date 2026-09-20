<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mfs40u4oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:virus-thin" /></template>
<style>
.mfs40u4oo {
  fill: currentColor;
  d: path("M132 108a24 24 0 1 0-24 24a24 24 0 0 0 24-24m-24 16a16 16 0 1 1 16-16a16 16 0 0 1-16 16m80 4a12 12 0 1 1-12-12a12 12 0 0 1 12 12m-48 48a12 12 0 1 1-12-12a12 12 0 0 1 12 12m100-52h-20.09a91.64 91.64 0 0 0-24.12-58.13l15-15a4 4 0 1 0-5.66-5.66l-15 15A91.64 91.64 0 0 0 132 36.09V16a4 4 0 0 0-8 0v20.09a91.64 91.64 0 0 0-58.13 24.12l-15-15a4 4 0 0 0-5.66 5.66l15 15A91.64 91.64 0 0 0 36.09 124H16a4 4 0 0 0 0 8h20.09a91.64 91.64 0 0 0 24.12 58.13l-15 15a4 4 0 0 0 5.66 5.66l15-15A91.64 91.64 0 0 0 124 219.91V240a4 4 0 0 0 8 0v-20.09a91.64 91.64 0 0 0 58.13-24.12l15 15a4 4 0 0 0 5.66-5.66l-15-15A91.64 91.64 0 0 0 219.91 132H240a4 4 0 0 0 0-8m-112 88a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84");
}

</style>
