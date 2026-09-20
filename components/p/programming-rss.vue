<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz2p-gb2y.css';
import '../../css/q/qlm8aybxt.css';
import '../../css/l/l8l993bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uz2p-gb2y"/><path class="qlm8aybxt"/><path class="l8l993bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:programming-rss" /></template>
