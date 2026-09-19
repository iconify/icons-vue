<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6x4u0bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g6x4u0bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vite-wordmark" /></template>
