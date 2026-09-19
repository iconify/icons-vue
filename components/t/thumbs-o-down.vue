<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aosvgyiyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<g transform="translate(0 1664) scale(1 -1)"><path class="aosvgyiyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thumbs-o-down" /></template>
