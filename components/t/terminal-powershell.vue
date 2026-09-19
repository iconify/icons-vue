<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgstyy1hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zgstyy1hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:terminal-powershell" /></template>
