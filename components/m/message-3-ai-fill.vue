<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ed6kb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8ed6kb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-3-ai-fill" /></template>
