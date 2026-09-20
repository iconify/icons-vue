<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeidf-brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qeidf-brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-area-stacked" /></template>
