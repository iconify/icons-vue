<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeg4hwboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-slight-right-outline-sharp" /></template>
<style>
.jeg4hwboi {
  fill: currentColor;
  d: path("M9.5 19.77v-7.69L15.6 6h-2.98V5h4.669v4.67h-1V6.688l-5.789 5.77v7.311z");
}

</style>
