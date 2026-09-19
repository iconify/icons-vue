<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybcv3hbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":2016};
const content = `<path class="ybcv3hbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:wine" /></template>
