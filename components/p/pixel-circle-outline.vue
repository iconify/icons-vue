<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgly6dx1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wgly6dx1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-circle-outline" /></template>
