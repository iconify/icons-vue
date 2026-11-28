<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ivfar3_lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-list-filter-sharp-fill" /></template>
<style>
.ivfar3_lb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2H21C21.552 2 22 2.448 22 3V21C22 21.552 21.552 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2ZM10 17H14V15H10V17ZM8.5 13H15.5V11H8.5V13ZM7 9H17V7H7V9Z");
}

</style>
