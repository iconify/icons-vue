<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipjfvdb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipjfvdb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-3-ai-line" /></template>
