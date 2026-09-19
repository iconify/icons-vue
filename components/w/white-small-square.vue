<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nrvmg4baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:white-small-square" /></template>
<style>
.nrvmg4baa {
  fill: currentColor;
  d: path("M46 18v28H18V18zm2-2H16v32h32z");
}

</style>
