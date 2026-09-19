<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doyrpzbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="doyrpzbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-typing-stroke-16" /></template>
