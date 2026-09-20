<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="em2_73l6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:square-split-horizontal-light" /></template>
<style>
.em2_73l6z {
  fill: currentColor;
  d: path("M200 42H56a14 14 0 0 0-14 14v144a14 14 0 0 0 14 14h144a14 14 0 0 0 14-14V56a14 14 0 0 0-14-14M54 200V56a2 2 0 0 1 2-2h66v148H56a2 2 0 0 1-2-2m148 0a2 2 0 0 1-2 2h-66V54h66a2 2 0 0 1 2 2Z");
}

</style>
