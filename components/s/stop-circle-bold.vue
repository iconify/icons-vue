<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ptea1lcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stop-circle-bold" /></template>
<style>
.ptea1lcbf {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m40-112v56a12 12 0 0 1-12 12h-56a12 12 0 0 1-12-12v-56a12 12 0 0 1 12-12h56a12 12 0 0 1 12 12");
}

</style>
