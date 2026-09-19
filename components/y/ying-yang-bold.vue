<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p1uypcbqv.css';
import '../../css/g/g7f03lbok.css';
import '../../css/m/m-u0l2bzu.css';
import '../../css/s/snq0_74tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="p1uypcbqv"/><path class="g7f03lbok"/><path clip-rule="evenodd" class="m-u0l2bzu"/><rect class="snq0_74tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ying-yang-bold" /></template>
