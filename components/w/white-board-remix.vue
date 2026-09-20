<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mst73-bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mst73-bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:white-board-remix" /></template>
