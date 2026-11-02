<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu1lzdgji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu1lzdgji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-2-ai-line" /></template>
