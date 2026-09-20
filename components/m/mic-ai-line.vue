<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3-p27eyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3-p27eyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-ai-line" /></template>
