<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn2f94bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn2f94bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:section-x" /></template>
