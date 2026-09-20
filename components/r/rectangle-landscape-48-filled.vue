<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2qsov7zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-landscape-48-filled" /></template>
<style>
.n2qsov7zh {
  fill: currentColor;
  d: path("M4 13.25C4 10.35 6.35 8 9.25 8h29.5c2.9 0 5.25 2.35 5.25 5.25v21.5c0 2.9-2.35 5.25-5.25 5.25H9.25A5.25 5.25 0 0 1 4 34.75z");
}

</style>
