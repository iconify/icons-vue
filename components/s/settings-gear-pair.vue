<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ml1gg0u1d"/><path class="ercesjbfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:settings-gear-pair" /></template>
<style>
.ercesjbfc {
  d: path("M6.75 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm9.983 6.359l.059-1.296h1.416l.059 1.296l1.136.656l1.152-.597l.709 1.227l-1.093.699v1.312l1.093.699l-.709 1.227l-1.152-.597l-1.136.656l-.059 1.296h-1.416l-.059-1.296l-1.136-.656l-1.152.597l-.709-1.227l1.093-.699v-1.312l-1.093-.699l.709-1.227l1.152.597Z");
}

.ml1gg0u1d {
  d: path("m7.553 4.101l.148-1.548h1.598l.148 1.548l1.494.619l1.199-.99l1.13 1.13l-.99 1.199l.619 1.494l1.548.148v1.598l-1.548.148l-.619 1.494l.99 1.199l-1.13 1.13l-1.199-.99l-1.494.619l-.148 1.548H7.701l-.148-1.548l-1.494-.619l-1.199.99l-1.13-1.13l.99-1.199l-.619-1.494l-1.548-.148V7.701l1.548-.148l.619-1.494l-.99-1.199l1.13-1.13l1.199.99Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
