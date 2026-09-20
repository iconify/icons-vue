<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nh4k-rbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:play-circle-bold" /></template>
<style>
.nh4k-rbal {
  fill: currentColor;
  d: path("M176 128a12 12 0 0 1-5.17 9.87l-52 36A12 12 0 0 1 100 164V92a12 12 0 0 1 18.83-9.87l52 36A12 12 0 0 1 176 128m60 0A108 108 0 1 1 128 20a108.12 108.12 0 0 1 108 108m-24 0a84 84 0 1 0-84 84a84.09 84.09 0 0 0 84-84");
}

</style>
