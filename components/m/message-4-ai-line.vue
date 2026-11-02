<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk99yguzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk99yguzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-4-ai-line" /></template>
