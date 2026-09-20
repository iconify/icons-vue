<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6iva4bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subheader-sharp" /></template>
<style>
.i6iva4bso {
  fill: currentColor;
  d: path("M6.616 9.192h8v-2h-8zM4 20V4h16v16z");
}

</style>
