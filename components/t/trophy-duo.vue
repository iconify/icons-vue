<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a0du3hboe.css';
import '../../css/k/kw3akl4eq.css';
import '../../css/l/l_wahk1-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="a0du3hboe"/><path class="kw3akl4eq"/><path class="l_wahk1-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:trophy-duo" /></template>
