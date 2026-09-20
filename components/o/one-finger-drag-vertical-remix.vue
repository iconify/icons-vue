<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2d8-qbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f2d8-qbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-finger-drag-vertical-remix" /></template>
