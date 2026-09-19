<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sixe4sxez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sixe4sxez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:select-window" /></template>
