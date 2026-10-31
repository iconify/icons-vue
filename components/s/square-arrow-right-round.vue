<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3stb3b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3stb3b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-right-round" /></template>
