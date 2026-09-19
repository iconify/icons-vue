<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rapo_tbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2208,"height":1664};
const content = `<path class="rapo_tbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:multi-arrow" /></template>
