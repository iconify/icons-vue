<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0kqh3fkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rule-folder-outline-sharp" /></template>
<style>
.m0kqh3fkb {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm1-1h16V8h-8.806l-2-2H4zm0 0V6zm3.825-2.336l4.239-4.239l-.714-.713l-3.525 3.53l-1.406-1.405l-.707.713zm6.575 0l1.6-1.6l1.6 1.6l.688-.689l-1.6-1.6l1.6-1.6l-.688-.688l-1.6 1.6l-1.6-1.6l-.688.688l1.6 1.6l-1.6 1.6z");
}

</style>
