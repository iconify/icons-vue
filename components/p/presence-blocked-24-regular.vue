<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo_45tb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-blocked-24-regular" /></template>
<style>
.zo_45tb6s {
  fill: currentColor;
  d: path("M24 12c0 6.627-5.373 12-12 12S0 18.627 0 12S5.373 0 12 0s12 5.373 12 12m-3 0a8.96 8.96 0 0 0-1.664-5.215L6.786 19.336A9 9 0 0 0 21 12m-3.785-7.336a9 9 0 0 0-12.55 12.55z");
}

</style>
