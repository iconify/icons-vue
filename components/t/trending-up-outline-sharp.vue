<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tefv-8bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trending-up-outline-sharp" /></template>
<style>
.tefv-8bar {
  fill: currentColor;
  d: path("M3.708 17.096L3 16.39l6.304-6.354l4 4l6.027-5.939H16v-1h5v5h-1V8.804L13.304 15.5l-4-4z");
}

</style>
