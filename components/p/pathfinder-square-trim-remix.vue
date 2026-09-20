<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-7d8qbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-7d8qbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pathfinder-square-trim-remix" /></template>
