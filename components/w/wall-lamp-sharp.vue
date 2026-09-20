<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4-agze3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wall-lamp-sharp" /></template>
<style>
.n4-agze3v {
  fill: currentColor;
  d: path("M3 21v-6h2v6zm3-2v-2h6v-4H5.65l3-10h8.7l3 10H14v6z");
}

</style>
