<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmsgpzf7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmsgpzf7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-4-ai-line" /></template>
