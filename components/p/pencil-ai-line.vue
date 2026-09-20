<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz8-0owbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz8-0owbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ai-line" /></template>
