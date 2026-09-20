<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhne4ccit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:south-west-outline" /></template>
<style>
.lhne4ccit {
  fill: currentColor;
  d: path("M5.5 18.5v-9h1v7.292l12.1-12.1l.708.708l-12.1 12.1H14.5v1z");
}

</style>
