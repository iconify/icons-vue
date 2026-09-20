<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yhj2esbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-large-square" /></template>
<style>
.yhj2esbqb {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M6.93 1C3.67 1 1 3.67 1 6.93v114.14c0 3.26 2.67 5.93 5.93 5.93h114.14c3.26 0 5.93-2.67 5.93-5.93V6.93c0-3.26-2.67-5.93-5.93-5.93z");
}

</style>
