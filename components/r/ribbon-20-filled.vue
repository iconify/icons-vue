<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1csjsvko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-20-filled" /></template>
<style>
.v1csjsvko {
  fill: currentColor;
  d: path("M16 8A6 6 0 1 1 4 8a6 6 0 0 1 12 0m-6 7a6.97 6.97 0 0 0 4-1.255V17.5a.5.5 0 0 1-.79.407L10 16l-3.21 1.907A.5.5 0 0 1 6 17.5v-3.755A6.97 6.97 0 0 0 10 15");
}

</style>
