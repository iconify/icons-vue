<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6mwrbb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-how-to-vote" /></template>
<style>
.g6mwrbb1y {
  fill: currentColor;
  d: path("M18 13h-.68l-2 2h1.91L19 17H5l1.78-2h2.05l-2-2H6l-3 3v4c0 1.1.89 2 1.99 2H19a2 2 0 0 0 2-2v-4zm1 7H5v-1h14zm-7.66-4.98c.39.39 1.02.39 1.41 0l6.36-6.36a.996.996 0 0 0 0-1.41L14.16 2.3a.975.975 0 0 0-1.4-.01L6.39 8.66a.996.996 0 0 0 0 1.41zm2.12-10.61L17 7.95l-4.95 4.95l-3.54-3.54z");
}

</style>
