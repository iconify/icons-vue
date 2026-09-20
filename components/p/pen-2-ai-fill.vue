<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_v7z0b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_v7z0b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-2-ai-fill" /></template>
