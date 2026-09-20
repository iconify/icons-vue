<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swegjjbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-select-jump-to-beginning-outline" /></template>
<style>
.swegjjbmm {
  fill: currentColor;
  d: path("M18.77 5.23V4H20v1.23zm0 14.77v-1.23H20V20zM15.076 5.23V4h1.23v1.23zm0 14.77v-1.23h1.23V20zM11.385 5.23V4h1.23v1.23zm-3.693 0V4h1.231v1.23zm0 14.77v-1.23h1.231V20zM4 20V4h1v16zm9.442-4.711L10.154 12l3.288-3.288l.708.688l-2.075 2.1H20v1h-7.925l2.075 2.1zM11.385 20v-1.23h1.23V20z");
}

</style>
