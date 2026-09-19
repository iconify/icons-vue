<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kqz1t_byv.css';
import '../../css/w/wl2pvqt_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="kqz1t_byv"/><path clip-rule="evenodd" class="wl2pvqt_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pencil-1-bold" /></template>
