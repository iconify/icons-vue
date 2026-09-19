<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uun356bhu.css';
import '../../css/j/jqddh6bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uun356bhu"/><path class="jqddh6bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rag" /></template>
