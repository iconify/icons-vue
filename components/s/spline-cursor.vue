<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z87kw4b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z87kw4b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:spline-cursor" /></template>
