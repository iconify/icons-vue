<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0_u48bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1536};
const content = `<g transform="translate(1024 0) scale(-1 1)"><path class="u0_u48bns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:step-forward" /></template>
