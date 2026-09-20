<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vboym7chi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vboym7chi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-cursor-input" /></template>
