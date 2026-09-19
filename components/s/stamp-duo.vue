<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d3_2_6jzi.css';
import '../../css/e/e8ud69wmt.css';
import '../../css/l/lkfkt8bbq.css';
import '../../css/f/fydgi61ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="d3_2_6jzi"/><path class="e8ud69wmt"/><path class="lkfkt8bbq"/><path class="fydgi61ch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stamp-duo" /></template>
