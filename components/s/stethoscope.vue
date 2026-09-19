<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmj46q_yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="fmj46q_yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:stethoscope" /></template>
