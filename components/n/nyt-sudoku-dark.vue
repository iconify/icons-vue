<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzcqqobzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzcqqobzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-sudoku-dark" /></template>
