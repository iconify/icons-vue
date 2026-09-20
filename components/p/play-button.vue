<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j9yjp7bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:play-button" /></template>
<style>
.j9yjp7bte {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M22 15.5v97L106 64z");
}

</style>
