<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3nk8bb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3nk8bb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:spa-candle" /></template>
