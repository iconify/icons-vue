<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xis5lhb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pageless-outline-sharp" /></template>
<style>
.xis5lhb-g {
  fill: currentColor;
  d: path("M2 21v-6.654h1V20h6.654v1zm12.346 0v-1H21v-5.654h1V21zM2 9.673V3h7.654v1H3v5.673zm19 0V4h-6.654V3H22v6.673z");
}

</style>
