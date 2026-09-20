<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqmbmgufy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-increase-sharp" /></template>
<style>
.qqmbmgufy {
  fill: currentColor;
  d: path("m1.616 18.5l5.288-13h.962l5.288 13h-1.208l-1.448-3.633H4.194L2.746 18.5zm2.938-4.6h5.584l-2.71-6.8h-.132zm13.83 1.6v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
