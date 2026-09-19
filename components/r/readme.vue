<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iovyd2lnb.css';
import '../../css/i/iio97lbyc.css';
import '../../css/e/e9vub8bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="iovyd2lnb"><path class="iio97lbyc"/><path class="e9vub8bzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:readme" /></template>
