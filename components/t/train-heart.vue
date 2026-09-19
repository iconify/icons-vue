<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djmwz3owo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="djmwz3owo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:train-heart" /></template>
