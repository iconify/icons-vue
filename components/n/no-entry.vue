<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty-y1pi4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ty-y1pi4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:no-entry" /></template>
