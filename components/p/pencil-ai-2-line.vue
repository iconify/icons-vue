<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_aahhbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_aahhbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ai-2-line" /></template>
