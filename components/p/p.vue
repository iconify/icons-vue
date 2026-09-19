<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohbqhs6vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ohbqhs6vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:p" /></template>
