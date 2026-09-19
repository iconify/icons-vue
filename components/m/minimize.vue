<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlak9g5tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dlak9g5tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:minimize" /></template>
