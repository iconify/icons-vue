<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_dqcbc8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b_dqcbc8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:uv" /></template>
