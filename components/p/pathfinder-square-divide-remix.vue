<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jee4jzbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jee4jzbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pathfinder-square-divide-remix" /></template>
