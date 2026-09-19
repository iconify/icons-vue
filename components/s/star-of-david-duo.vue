<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/glrfvfvss.css';
import '../../css/l/l-tj_lb7g.css';
import '../../css/z/zctcw55nb.css';
import '../../css/s/swtvqgbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="glrfvfvss"/><path class="l-tj_lb7g"/><path class="zctcw55nb"/><path class="swtvqgbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-of-david-duo" /></template>
