<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gptlxqbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gptlxqbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tiktok-line" /></template>
