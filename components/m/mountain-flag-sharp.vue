<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi6u_jbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mountain-flag-sharp" /></template>
<style>
.gi6u_jbdi {
  fill: currentColor;
  d: path("M7.64 12.825L9.036 10H11.5V3h5.692l-.75 1.5l.75 1.5H12.5v4h2.385l1.424 2.87l-2.346 1.557L12 13.433l-1.964.994zM3.616 21l3.587-7.279l2.762 1.852L12 14.567l2.036 1.006l2.731-1.802L20.385 21z");
}

</style>
