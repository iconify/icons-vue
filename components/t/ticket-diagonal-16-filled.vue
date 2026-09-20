<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xgmtav3rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-16-filled" /></template>
<style>
.xgmtav3rz {
  fill: currentColor;
  d: path("M8.165 1.513a1.75 1.75 0 0 1 2.475 0l.494.494c.342.342.249.843-.018 1.109a1.25 1.25 0 1 0 1.767 1.767l.11-.093c.258-.177.64-.219.932.015l.066.06l.496.495a1.75 1.75 0 0 1 0 2.474l-1.972 1.972l-.777-.777a.5.5 0 0 0-.707.707l.777.777l-3.975 3.976c-.64.64-1.654.68-2.342.12l-.132-.12l-.496-.496c-.342-.342-.249-.843.018-1.109l.081-.089a1.25 1.25 0 0 0-1.848-1.677c-.265.267-.766.36-1.108.018l-.494-.494a1.75 1.75 0 0 1 0-2.476l3.975-3.974l.776.776a.5.5 0 0 0 .707-.707l-.776-.776zm.573 4.516a.5.5 0 0 0-.707.707l1.232 1.232a.5.5 0 0 0 .707-.707z");
}

</style>
