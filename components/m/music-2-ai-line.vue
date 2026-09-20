<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfiksmb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfiksmb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-2-ai-line" /></template>
