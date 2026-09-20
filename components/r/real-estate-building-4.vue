<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylvg4v1fy.css';
import '../../css/h/hsx1pzxph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ylvg4v1fy"/><path class="hsx1pzxph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:real-estate-building-4" /></template>
