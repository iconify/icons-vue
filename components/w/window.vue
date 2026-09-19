<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_wvbn4-s.css';
import '../../css/b/bfe2smrhu.css';
import '../../css/x/xbdrabtly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="p_wvbn4-s"><path class="bfe2smrhu"/><path class="xbdrabtly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:window" /></template>
