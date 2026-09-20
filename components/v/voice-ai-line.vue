<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdq-b1j7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdq-b1j7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:voice-ai-line" /></template>
