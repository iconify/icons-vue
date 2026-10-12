<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrexurzup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:succulent-sharp" /></template>
<style>
.rrexurzup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5c-1.75-1.5-2.25-4.75 0-9c2.25 4.25 1.75 7.5 0 9Zm-3 .75c-2.75 0-5.25-1.5-6.25-4c3.25 0 5.5 1.25 6.25 4Zm6 0c2.75 0 5.25-1.5 6.25-4c-3.25 0-5.5 1.25-6.25 4ZM6.5 16h11l-1.15 4.35l-.262.9H7.913l-.263-.9Z");
}

</style>
