<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7lu1v5bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7lu1v5bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scallop" /></template>
