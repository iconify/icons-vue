<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<path class="p23co8mne"/><path class="m73451bht"/><path class="mp9ucpbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:new-relic-icon" /></template>
<style>
.m73451bht {
  fill: var(--svg-color--1ce783, #1ce783);
  d: path("m128 56.86l78.745 45.462L256 73.892L128 0L0 73.892l49.236 28.43z");
}

.mp9ucpbao {
  fill: var(--svg-color--1d252c, #1d252c);
  d: path("M78.764 176.232v90.943L128 295.586V147.802L0 73.892v56.86z");
}

.p23co8mne {
  fill: var(--svg-color--00ac69, #00ac69);
  d: path("M206.745 102.322v90.942L128 238.745v56.841l128-73.892V73.892z");
}

</style>
