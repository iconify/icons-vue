<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk2lrzbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xk2lrzbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:o" /></template>
