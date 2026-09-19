<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjzd3-bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="xjzd3-bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:rocket" /></template>
