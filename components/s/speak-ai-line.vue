<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wws1cbc7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wws1cbc7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speak-ai-line" /></template>
