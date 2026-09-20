<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thy1wvbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-90-left-16-regular" /></template>
<style>
.thy1wvbmd {
  fill: currentColor;
  d: path("M4.146 2.147a.5.5 0 0 1 .707 0l2 2a.5.5 0 0 1-.707.707L5 3.707V13.5a.5.5 0 0 1-1 0V3.707L2.853 4.854a.5.5 0 0 1-.707-.707zM6.533 8.32a.5.5 0 0 1 .647-.287l6.5 2.5l.069.033a.5.5 0 0 1-.07.9l-6.5 2.5a.5.5 0 0 1-.359-.933L9 12.194v-2.39l-2.18-.837a.5.5 0 0 1-.287-.647M10 11.81l2.107-.81L10 10.19zm.146-9.663a.5.5 0 0 1 .707 0l2 2a.5.5 0 0 1-.707.707L11 3.707V7.5a.5.5 0 0 1-1 0V3.707L8.853 4.854a.5.5 0 0 1-.707-.707z");
}

</style>
