<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uor91wbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uor91wbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:shinto-shrine" /></template>
