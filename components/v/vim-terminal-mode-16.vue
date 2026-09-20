<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyp7mkbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dyp7mkbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-terminal-mode-16" /></template>
