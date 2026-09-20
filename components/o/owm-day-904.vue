<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in3i6fb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="in3i6fb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-904" /></template>
