<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5v64fbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5v64fbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-ai-fill" /></template>
