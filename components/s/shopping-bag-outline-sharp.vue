<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejc2n6c7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-bag-outline-sharp" /></template>
<style>
.ejc2n6c7z {
  fill: currentColor;
  d: path("M4 22V6h4q0-1.65 1.175-2.825T12 2t2.825 1.175T16 6h4v16zm2-2h12V8h-2v3h-2V8h-4v3H8V8H6zm4-14h4q0-.825-.587-1.412T12 4t-1.412.588T10 6M6 20V8z");
}

</style>
