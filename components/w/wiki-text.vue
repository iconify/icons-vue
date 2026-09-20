<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbxarv7vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sbxarv7vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:wiki-text" /></template>
