<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f5dkyacpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:taurus" /></template>
<style>
.f5dkyacpg {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M90.47 42.88c10.77-8.09 17.79-20.92 17.79-35.39H90.51C90.51 22.1 78.61 34 64 34C49.38 34 37.49 22.1 37.49 7.49H19.75c0 14.47 7.01 27.3 17.79 35.39c-10.77 8.08-17.79 20.91-17.79 35.39c0 24.39 19.85 44.25 44.25 44.25s44.25-19.85 44.25-44.25c0-14.49-7.01-27.32-17.78-35.39M64 104.76c-14.62 0-26.51-11.89-26.51-26.5c0-14.62 11.89-26.51 26.51-26.51c14.61 0 26.51 11.89 26.51 26.51s-11.9 26.5-26.51 26.5");
}

</style>
