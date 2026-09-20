<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvfgygbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvfgygbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:webcam" /></template>
