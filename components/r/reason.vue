<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhb8c01ug.css';
import '../../css/y/yeq9_s_cg.css';
import '../../css/c/c1y_6pbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="yeq9_s_cg"/><path class="c1y_6pbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:reason" /></template>
