<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5ip3tbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tornado-outline-sharp" /></template>
<style>
.n5ip3tbvz {
  fill: currentColor;
  d: path("M1 3h22L12 22zm3.475 2L6.2 8h11.6l1.725-3zm2.9 5L9.1 13h5.8l1.725-3zm2.9 5L12 18l1.725-3z");
}

</style>
