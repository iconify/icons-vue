<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b66t3qfwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-arrow-outline-rounded" /></template>
<style>
.b66t3qfwb {
  fill: currentColor;
  d: path("M9 15.714V8.287q0-.368.242-.588t.566-.22q.106 0 .214.028q.109.027.215.083l5.842 3.733q.186.13.28.298q.093.167.093.379t-.093.379t-.28.298l-5.843 3.733q-.105.055-.214.083q-.108.028-.214.028q-.323 0-.566-.22T9 15.714m1-.364L15.289 12L10 8.65z");
}

</style>
