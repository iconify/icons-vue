<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-g7-bxba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i-g7-bxba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:project-compact" /></template>
