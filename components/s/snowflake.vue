<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0keeccyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l0keeccyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:snowflake" /></template>
