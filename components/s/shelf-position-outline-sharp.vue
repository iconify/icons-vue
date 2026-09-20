<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0v5varzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shelf-position-outline-sharp" /></template>
<style>
.u0v5varzx {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-3.5H5zm11.116-4.5H19V5h-2.884zM5 14.5h2.885V5H5zm3.885 0h6.23V5h-6.23z");
}

</style>
