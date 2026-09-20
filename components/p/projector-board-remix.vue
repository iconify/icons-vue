<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw1jr1bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fw1jr1bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:projector-board-remix" /></template>
