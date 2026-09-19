<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yti0hccuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yti0hccuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:toy-mallet" /></template>
