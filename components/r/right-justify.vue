<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc4w2nyzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tc4w2nyzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:right-justify" /></template>
