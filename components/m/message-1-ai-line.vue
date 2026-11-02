<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjz2s1uvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjz2s1uvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-1-ai-line" /></template>
