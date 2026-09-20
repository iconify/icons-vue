<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gecrqn4vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gecrqn4vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-3-ai-line" /></template>
