<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgezfpb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgezfpb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qwen-ai-fill" /></template>
