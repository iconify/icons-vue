<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hig_nhbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hig_nhbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-sudoku-light" /></template>
