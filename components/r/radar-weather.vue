<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_m7qkb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y_m7qkb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:radar-weather" /></template>
