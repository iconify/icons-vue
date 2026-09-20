<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz3yzsstx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="fz3yzsstx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-200" /></template>
