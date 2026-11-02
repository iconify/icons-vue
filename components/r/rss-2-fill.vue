<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qczb0h48q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qczb0h48q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rss-2-fill" /></template>
