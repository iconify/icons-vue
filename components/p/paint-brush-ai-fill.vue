<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjr6b_b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cjr6b_b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-brush-ai-fill" /></template>
