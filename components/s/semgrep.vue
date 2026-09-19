<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwy1apbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qwy1apbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:semgrep" /></template>
