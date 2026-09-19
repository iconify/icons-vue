<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnwxg_aar.css';
import '../../css/v/v5-1tabpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="qnwxg_aar"/><path class="v5-1tabpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:stata" /></template>
