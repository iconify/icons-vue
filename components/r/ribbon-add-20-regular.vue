<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lzgc84bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-add-20-regular" /></template>
<style>
.lzgc84bfn {
  fill: currentColor;
  d: path("M19 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V5h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V6h1.5a.5.5 0 0 0 0-1H15zM9 2q.6.001 1.166.113q-.337.43-.583.92a5 5 0 1 0 3.542 7.793q.521.136 1.077.166A6 6 0 0 1 13 12.472V17.5a.5.5 0 0 1-.748.434L9 16.076l-3.252 1.858A.5.5 0 0 1 5 17.5v-5.028A6 6 0 0 1 9 2m0 12a6 6 0 0 1-3-.803v3.441l2.752-1.572a.5.5 0 0 1 .496 0L12 16.638v-3.44A6 6 0 0 1 9 14");
}

</style>
