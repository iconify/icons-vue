<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7k-jac0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7k-jac0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:movie-ai-line" /></template>
