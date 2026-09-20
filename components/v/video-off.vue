<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa6llmypj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa6llmypj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:video-off" /></template>
