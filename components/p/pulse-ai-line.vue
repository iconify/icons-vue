<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc32zubtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc32zubtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pulse-ai-line" /></template>
