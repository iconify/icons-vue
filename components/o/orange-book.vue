<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvxx72bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vvxx72bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:orange-book" /></template>
