<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvflfbb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dvflfbb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pentagon-left-outline" /></template>
