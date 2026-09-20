<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuhdtfbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:price-check-sharp" /></template>
<style>
.tuhdtfbxg {
  fill: currentColor;
  d: path("M6.5 14.975v-1H4v-2h5v-2H4v-6h2.5v-1h2v1H11v2H6v2h5v6H8.5v1zm7.45 6l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4z");
}

</style>
