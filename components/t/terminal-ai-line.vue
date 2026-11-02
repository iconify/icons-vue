<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5drg8byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5drg8byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-ai-line" /></template>
