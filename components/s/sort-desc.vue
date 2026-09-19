<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrpqgccob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1344};
const content = `<g transform="translate(0 1344) scale(1 -1)"><path class="yrpqgccob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sort-desc" /></template>
