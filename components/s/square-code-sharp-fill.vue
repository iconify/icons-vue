<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzzrvab6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-code-sharp-fill" /></template>
<style>
.tzzrvab6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM9.54 7.5L6.2407 11.3492C6.0854 11.5305 6 11.7613 6 12C6 12.2387 6.0854 12.4695 6.2407 12.6508L9.54 16.5L11.0586 15.1984L8.3171 12L11.0586 8.8016L9.54 7.5ZM14.46 7.5L17.7593 11.3492C17.9146 11.5305 18 11.7613 18 12C18 12.2387 17.9146 12.4695 17.7593 12.6508L14.46 16.5L12.9414 15.1984L15.6829 12L12.9414 8.8016L14.46 7.5Z");
}

</style>
