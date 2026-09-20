<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="khhw3-yhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-multiple-16-filled" /></template>
<style>
.khhw3-yhs {
  fill: currentColor;
  d: path("M4.5 2H5v1.5A1.5 1.5 0 0 0 6.5 5H12v4.5A2.5 2.5 0 0 1 9.5 12h-5A2.5 2.5 0 0 1 2 9.5v-5A2.5 2.5 0 0 1 4.5 2m5 0a2.5 2.5 0 0 1 2.45 2H6.5a.5.5 0 0 1-.5-.5V2zM4.498 13c.456.608 1.182 1 2 1h3.5a4 4 0 0 0 4-4V6.5c0-.816-.391-1.542-.997-1.998V9.5l-.002.114V10a3 3 0 0 1-3 3z");
}

</style>
