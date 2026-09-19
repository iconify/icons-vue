<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuh_7mbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fuh_7mbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pen" /></template>
