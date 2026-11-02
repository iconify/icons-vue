<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaknn7bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaknn7bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-2-ai-fill" /></template>
