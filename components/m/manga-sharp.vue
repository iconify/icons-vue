<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsfd8mb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:manga-sharp" /></template>
<style>
.vsfd8mb3b {
  fill: currentColor;
  d: path("M3 19V5h18v14zm5.735-1h10.65q.23 0 .423-.192t.192-.424v-9.84l-3 .975l-2.883-.923l-1.807 2.46l-2.886.938v3.046L7.641 16.5z");
}

</style>
