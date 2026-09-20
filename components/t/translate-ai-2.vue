<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryi3-obbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryi3-obbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:translate-ai-2" /></template>
