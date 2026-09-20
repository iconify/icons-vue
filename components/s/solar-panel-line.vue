<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb9y4lqfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb9y4lqfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:solar-panel-line" /></template>
