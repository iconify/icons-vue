<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysfngxbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysfngxbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-ai-fill" /></template>
