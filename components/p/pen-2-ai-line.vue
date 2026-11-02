<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vryobju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5vryobju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-2-ai-line" /></template>
