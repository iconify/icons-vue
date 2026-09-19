<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgs-q4b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="zgs-q4b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:square-plus" /></template>
