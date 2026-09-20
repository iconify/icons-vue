<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0klx1dfy.css';
import '../../css/n/nr9_5n4qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g transform="matrix(1.5 0 0 1.5 -23.858 -7.25)"><path class="x0klx1dfy"/><rect class="nr9_5n4qz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:opencode" /></template>
