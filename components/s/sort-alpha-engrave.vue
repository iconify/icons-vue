<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mkbzfbcab.css';
import '../../css/a/a4hjggb0v.css';
import '../../css/v/vuzeqx4xo.css';
import '../../css/u/u315dy91q.css';
import '../../css/l/lof7i1b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mkbzfbcab wm-k"/><path class="a4hjggb0v wm-a"/><path class="vuzeqx4xo wm-shadow"/><path class="u315dy91q wm-k"/><path class="lof7i1b0v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sort-alpha-engrave" /></template>
