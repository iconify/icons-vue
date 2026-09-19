<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhb8c01ug.css';
import '../../css/w/w03w98eed.css';
import '../../css/v/vzmjekozx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="w03w98eed"/><path class="vzmjekozx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rescript" /></template>
