<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg-3enm4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-data-setting-sharp" /></template>
<style>
.pg-3enm4m {
  fill: currentColor;
  d: path("M19.941 19.403q.636-.636.636-1.518q0-.883-.636-1.519q-.635-.635-1.518-.635q-.882 0-1.518.635q-.636.636-.636 1.519t.636 1.518t1.518.636t1.518-.636m-2.018 2.366l-.107-.884q-.57-.125-.938-.33q-.369-.205-.701-.578l-.835.335l-.538-.816l.688-.577q-.165-.53-.165-1.034t.165-1.035l-.688-.577l.538-.815l.835.334q.333-.392.701-.587t.938-.32l.107-.885h1l.108.885q.569.125.937.32t.701.587l.835-.334l.538.815l-.688.577q.165.53.165 1.035t-.165 1.034l.688.577l-.538.816l-.835-.335q-.332.373-.7.578t-.938.33l-.108.884zM3 21L21 3v9.17q-.592-.287-1.26-.43t-1.336-.144q-2.637 0-4.475 1.836q-1.839 1.835-1.839 4.472q0 .76.214 1.6q.213.84.607 1.496z");
}

</style>
