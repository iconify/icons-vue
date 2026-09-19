<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkvr8kb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vkvr8kb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:music" /></template>
