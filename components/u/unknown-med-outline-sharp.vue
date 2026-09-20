<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttpw3gb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unknown-med-outline-sharp" /></template>
<style>
.ttpw3gb6h {
  fill: currentColor;
  d: path("M2 13v-3h9v3zm11 0v-3h9v3z");
}

</style>
