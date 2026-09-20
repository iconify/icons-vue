<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isut04vzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skillet-outline-sharp" /></template>
<style>
.isut04vzb {
  fill: currentColor;
  d: path("M3 19v-6h13v-1.648l5.848-1.956l.318.938L17 12.072V19zm1-1h12v-4H4zm1.483-7.384q.119-.824-.1-1.504T4.534 7.5q-.672-.98-.905-1.763q-.235-.78-.156-1.737h1.008q-.085.835.11 1.492q.196.658.828 1.589q.7 1.015.934 1.797t.138 1.738zm3.923 0q.119-.824-.096-1.504q-.216-.681-.848-1.612q-.671-.98-.908-1.762T7.396 4h1.008q-.085.835.11 1.492q.196.658.828 1.589q.7 1.015.934 1.797t.138 1.738zm4 0q.119-.824-.106-1.504T12.442 7.5q-.67-.98-.898-1.763T11.396 4h1.008q-.085.835.11 1.492q.196.658.828 1.589q.7 1.015.934 1.797t.138 1.738z");
}

</style>
