<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unb_--zap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unb_--zap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:textbox-ai-line" /></template>
