<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r77jbfzlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toc-outline" /></template>
<style>
.r77jbfzlu {
  fill: currentColor;
  d: path("M4 15.885v-1h12.346v1zM4 12.5v-1h12.346v1zm0-3.384v-1h12.346v1zM19.385 16q-.262 0-.439-.171t-.177-.425q0-.27.177-.452q.177-.183.439-.183q.261 0 .438.183q.177.182.177.452q0 .253-.177.425t-.438.171m0-3.366q-.262 0-.439-.172T18.77 12q0-.253.177-.425t.439-.171t.438.171T20 12q0 .29-.177.463q-.177.172-.438.172m0-3.404q-.262 0-.439-.172t-.177-.424q0-.27.177-.452q.177-.183.438-.183q.262 0 .439.183q.177.182.177.452q0 .253-.177.424q-.177.172-.438.172");
}

</style>
