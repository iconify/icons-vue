<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruvov2dhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruvov2dhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:toke-square" /></template>
