<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d98-p5wvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d98-p5wvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:teleport" /></template>
