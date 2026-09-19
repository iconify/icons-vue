<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoizpacxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xoizpacxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:waning-crescent-moon" /></template>
