<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rneu14raf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rneu14raf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:vercel" /></template>
