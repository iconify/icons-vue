<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyikixfvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfloat-landscape-outline-sharp" /></template>
<style>
.jyikixfvw {
  fill: currentColor;
  d: path("M2 20V4h20v7h-2V6H4v12h11v2Zm9.075-5.5l1.425-1.425L9.4 10H12V8H6v6h2v-2.575ZM17 20v-7h5v7Zm-5-8Z");
}

</style>
