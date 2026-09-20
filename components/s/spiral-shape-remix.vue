<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpxq-4mas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fpxq-4mas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:spiral-shape-remix" /></template>
