<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gssnz_6uu.css';
import '../../css/q/q4g7x6byd.css';
import '../../css/f/fv8g9ogfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gssnz_6uu"/><path class="q4g7x6byd"/><path class="fv8g9ogfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:turn-sign-duo" /></template>
