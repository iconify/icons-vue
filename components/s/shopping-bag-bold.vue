<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a__s2g6zp.css';
import '../../css/u/ure5rybbd.css';
import '../../css/i/i-nfk4xyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="ure5rybbd"/><path class="i-nfk4xyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-bag-bold" /></template>
