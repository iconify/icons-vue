<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":179};
const content = `<path class="qgmjk6buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nuodb" /></template>
<style>
.qgmjk6buv {
  d: path("M225.828 8.069l-13.283.79l-29.57 80.032l-35.22-41.22l-13.935-3.477L62.471 0l13.843 45.046l.036.205l-36.514-5.127l40.425 77.81l38.36 25.166L0 178.65l164.053-19.231l-.043-28.359l5.613-1.644l41.353-12.088l12.105-90.103L256 48.659l-30.172-40.59");
  fill: var(--svg-color--b5d118, #B5D118);
}

</style>
