<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct-uv_utb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ct-uv_utb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbnail-1" /></template>
