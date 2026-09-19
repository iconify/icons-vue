<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1e067yag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-horizontal-rule" /></template>
<style>
.e1e067yag {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 11h16v2H4z");
}

</style>
