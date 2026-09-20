<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn47gybec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-rotate-90-24-regular" /></template>
<style>
.pn47gybec {
  fill: currentColor;
  d: path("M18.25 2a.75.75 0 0 1 .75.75v18.5a.75.75 0 0 1-1.5 0V2.75a.75.75 0 0 1 .75-.75m-13 0a.75.75 0 0 1 .75.75v18.5a.75.75 0 0 1-1.5 0V2.75A.75.75 0 0 1 5.25 2m7.25.75a.75.75 0 0 0-1.5 0v18.5a.75.75 0 0 0 1.5 0z");
}

</style>
