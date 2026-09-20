<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_t018vfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_t018vfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-box-ai-line" /></template>
