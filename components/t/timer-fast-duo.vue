<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gfb_y0bgv.css';
import '../../css/t/tz3jlipja.css';
import '../../css/g/gf6_545td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gfb_y0bgv"/><path class="tz3jlipja"/><path class="gf6_545td"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:timer-fast-duo" /></template>
