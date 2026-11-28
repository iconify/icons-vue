<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="asq1horyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-middle-sharp-fill" /></template>
<style>
.asq1horyb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM6 9L6 11L18 11L18 9ZM6 13L6 15L14 15L14 13Z");
}

</style>
