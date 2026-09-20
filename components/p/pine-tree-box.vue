<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qszp67b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qszp67b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pine-tree-box" /></template>
