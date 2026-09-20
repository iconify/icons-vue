<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq7uilbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="vq7uilbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:split-three" /></template>
