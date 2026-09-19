<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z03t39b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z03t39b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:satellite-weather" /></template>
