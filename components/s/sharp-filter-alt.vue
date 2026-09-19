<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-b_ctaqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-alt" /></template>
<style>
.b-b_ctaqj {
  fill: currentColor;
  d: path("M3 4c2.01 2.59 7 9 7 9v7h4v-7s4.98-6.41 7-9z");
}

</style>
