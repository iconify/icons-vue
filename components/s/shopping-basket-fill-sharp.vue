<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzc1qhe1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-fill-sharp" /></template>
<style>
.nzc1qhe1u {
  fill: currentColor;
  d: path("M3 9h1.465l3.703-5.555a1 1 0 0 1 1.664 1.11L6.869 9h10.262l-2.963-4.445a1 1 0 0 1 1.664-1.11L19.535 9H21a1 1 0 0 1 0 2h-.18l-1.839 9.196A1 1 0 0 1 18 21H6a1 1 0 0 1-.981-.804L3.18 11H3a1 1 0 0 1 0-2m8 8v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4 0v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0");
}

</style>
