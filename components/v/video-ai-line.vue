<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5x90lkys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5x90lkys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-ai-line" /></template>
