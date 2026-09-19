<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7d5vnbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t7d5vnbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:mjml" /></template>
