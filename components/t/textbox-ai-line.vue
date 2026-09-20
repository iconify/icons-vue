<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zao_biosz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zao_biosz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:textbox-ai-line" /></template>
