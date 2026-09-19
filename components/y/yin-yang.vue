<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuq0kccjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yuq0kccjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:yin-yang" /></template>
