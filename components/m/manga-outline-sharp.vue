<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itp0ixwcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:manga-outline-sharp" /></template>
<style>
.itp0ixwcp {
  fill: currentColor;
  d: path("M2 20V4h20v16zm6.1-2l-1.075-1.5l1.9-2.625v-3.25l3.075-1L13.925 7L17 8l3-.975V6H4v12zm2.475 0H20v-7.725l-.675-.925L17 10.1l-2.3-.75l-1.45 1.975l-2.325.75v2.45L9.5 16.5z");
}

</style>
