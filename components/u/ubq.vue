<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t37cpkbel.css';
import '../../css/w/w17eqfq2x.css';
import '../../css/i/i6q2iqb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="t37cpkbel"/><path class="w17eqfq2x"/><path class="i6q2iqb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:ubq" /></template>
