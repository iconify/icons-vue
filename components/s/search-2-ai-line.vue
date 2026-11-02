<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvjty8bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvjty8bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-2-ai-line" /></template>
