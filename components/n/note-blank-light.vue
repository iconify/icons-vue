<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a1ck-ub5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:note-blank-light" /></template>
<style>
.a1ck-ub5y {
  fill: currentColor;
  d: path("M208 34H48a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h108.69a13.94 13.94 0 0 0 9.9-4.1l51.31-51.31a13.94 13.94 0 0 0 4.1-9.9V48a14 14 0 0 0-14-14M46 208V48a2 2 0 0 1 2-2h160a2 2 0 0 1 2 2v106h-50a6 6 0 0 0-6 6v50H48a2 2 0 0 1-2-2m120-6.49V166h35.52Z");
}

</style>
