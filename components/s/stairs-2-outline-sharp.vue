<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-j44fq2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stairs-2-outline-sharp" /></template>
<style>
.v-j44fq2d {
  fill: currentColor;
  d: path("M2 19v-2h6v-6h6V5h8v2h-6v6h-6v6z");
}

</style>
