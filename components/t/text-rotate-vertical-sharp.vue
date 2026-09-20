<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyoahuqff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-rotate-vertical-sharp" /></template>
<style>
.yyoahuqff {
  fill: currentColor;
  d: path("m11.63 15.654l3.91-10.308h1l3.83 10.308h-1.015l-1.038-2.838h-4.631l-1.039 2.838zm2.374-3.708h3.992l-1.907-5.28h-.1zm-7.965 7.362L3.23 16.5l.708-.708l1.6 1.512V3.5h1v13.804l1.6-1.512l.707.708z");
}

</style>
