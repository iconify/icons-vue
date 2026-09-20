<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdjftqb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdjftqb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:restore" /></template>
