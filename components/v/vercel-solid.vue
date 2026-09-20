<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezoeocn7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezoeocn7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:vercel-solid" /></template>
