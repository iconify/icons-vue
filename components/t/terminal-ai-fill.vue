<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp8fpmbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp8fpmbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-ai-fill" /></template>
