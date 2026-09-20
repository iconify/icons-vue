<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o34hezwxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trademark-bold" /></template>
<style>
.o34hezwxh {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m64-104v40a12 12 0 0 1-24 0v-13.91l-8.19 7a12 12 0 0 1-15.62 0l-8.19-7V148a12 12 0 0 1-24 0v-28h-12v28a12 12 0 0 1-24 0v-28h-4a12 12 0 0 1 0-24h52a12 12 0 0 1 7.81 2.89L152 116.2l20.19-17.31A12 12 0 0 1 192 108");
}

</style>
