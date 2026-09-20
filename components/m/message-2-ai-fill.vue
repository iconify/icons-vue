<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5vkv6bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5vkv6bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-2-ai-fill" /></template>
