<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_lt1cjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c-_lt1cjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:timeline-matrix-view" /></template>
