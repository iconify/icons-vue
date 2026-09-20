<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7llmqrei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m7llmqrei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-rain-wind" /></template>
