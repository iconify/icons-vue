<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7qn5succ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7qn5succ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-ai-fill" /></template>
