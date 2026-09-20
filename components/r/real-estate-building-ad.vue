<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8x1q1cuv.css';
import '../../css/a/aw90g_bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8x1q1cuv"/><path class="aw90g_bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:real-estate-building-ad" /></template>
