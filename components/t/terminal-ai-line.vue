<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7x-tob6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7x-tob6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-ai-line" /></template>
