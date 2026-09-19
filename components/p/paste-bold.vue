<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jvi2atbia.css';
import '../../css/f/f3pw89b2c.css';
import '../../css/j/j34gbswxf.css';
import '../../css/o/o_b_kpgnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="jvi2atbia"/><path clip-rule="evenodd" class="f3pw89b2c"/><path class="j34gbswxf"/><path clip-rule="evenodd" class="o_b_kpgnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:paste-bold" /></template>
