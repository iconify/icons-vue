<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-64-ji5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-restaurant" /></template>
<style>
.u-64-ji5t {
  fill: currentColor;
  d: path("M16.8 11H7.225l-.275 2h10.1zM4 20l1.225-9H3q-.5 0-.788-.4t-.162-.875l1.425-5q.1-.325.35-.525t.6-.2h15.15q.35 0 .6.2t.35.525l1.425 5q.125.475-.162.875T21 11h-2.2l1.2 9h-2l-.675-5H6.675L6 20z");
}

</style>
