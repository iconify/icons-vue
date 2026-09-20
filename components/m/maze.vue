<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew-n46vse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ew-n46vse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:maze" /></template>
