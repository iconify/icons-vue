<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx5pwg-0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pen-size-4-sharp" /></template>
<style>
.bx5pwg-0k {
  fill: currentColor;
  d: path("M5.48 16.496q0-.843.591-1.425l9-9q.582-.59 1.425-.59t1.433.59t.59 1.433t-.59 1.425l-9 9q-.582.59-1.425.59t-1.433-.59t-.59-1.433");
}

</style>
