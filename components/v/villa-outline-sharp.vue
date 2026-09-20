<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdsi0rwka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:villa-outline-sharp" /></template>
<style>
.rdsi0rwka {
  fill: currentColor;
  d: path("M4 20V8.692l11.23-4.326V13h1.693q0-.635.452-1.086q.451-.453 1.085-.453t1.087.452T20 13v7zm1-1h5v-6h4.23V5.804L5 9.375zm6 0h3.23v-2.308h1.54V19H19v-5h-8zm4-.654");
}

</style>
