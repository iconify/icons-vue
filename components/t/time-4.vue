<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx9lulxcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="hx9lulxcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-4" /></template>
