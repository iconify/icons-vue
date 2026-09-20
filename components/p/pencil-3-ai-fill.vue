<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efxcg-bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efxcg-bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-3-ai-fill" /></template>
