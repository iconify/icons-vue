<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c14c-h18e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c14c-h18e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sliders-vertical" /></template>
