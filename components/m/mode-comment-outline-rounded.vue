<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liklocc2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mode-comment-outline-rounded" /></template>
<style>
.liklocc2l {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v15.575q0 .675-.612.938T20.3 20.3L18 18zm14.85-2L20 17.125V4H4v12zM4 16V4z");
}

</style>
