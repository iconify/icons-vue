<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drkpzc5wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="drkpzc5wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-circle" /></template>
