<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsjnptbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsjnptbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-3-ai-fill" /></template>
