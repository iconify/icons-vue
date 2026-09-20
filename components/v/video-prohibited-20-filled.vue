<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_nabyklo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-20-filled" /></template>
<style>
.e_nabyklo {
  fill: currentColor;
  d: path("M5.5 9a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2.096 7.303a3.5 3.5 0 0 0 4.898-4.898zM10 4a3 3 0 0 1 3 3v6a3 3 0 0 1-2.587 2.97A5.5 5.5 0 0 0 2 9.257V7a3 3 0 0 1 3-3zm-4.5 6a3.5 3.5 0 0 0-2.803 5.596l4.899-4.899A3.5 3.5 0 0 0 5.5 10m10.537-4.776a1.25 1.25 0 0 1 1.96 1.028v7.495a1.25 1.25 0 0 1-1.96 1.028L14 13.37V6.63z");
}

</style>
