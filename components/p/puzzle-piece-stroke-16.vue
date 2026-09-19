<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fakckpsqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fakckpsqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:puzzle-piece-stroke-16" /></template>
