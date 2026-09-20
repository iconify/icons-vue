<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_bo_ccyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q_bo_ccyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smoke-detector" /></template>
