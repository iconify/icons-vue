<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhb8c01ug.css';
import '../../css/r/rirt7bcol.css';
import '../../css/m/mzxbszjzr.css';
import '../../css/d/dmlxnibql.css';
import '../../css/r/ryby98ucd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="rirt7bcol"/><path class="mzxbszjzr"/><path class="dmlxnibql"/><path class="ryby98ucd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:postcss" /></template>
