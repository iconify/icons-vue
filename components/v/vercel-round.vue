<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frhctlyvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frhctlyvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vercel-round" /></template>
