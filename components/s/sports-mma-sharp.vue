<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owk383bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sports-mma-sharp" /></template>
<style>
.owk383bfb {
  fill: currentColor;
  d: path("M7 21v-4h10v4zm-1-5l-1-5.05V3h12v4h2v3.95L18 16zm2-6h6V7H8z");
}

</style>
