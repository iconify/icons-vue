<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e8hb2u8yg.css';
import '../../css/y/yd2z58hmr.css';
import '../../css/g/gv0c9mbvs.css';
import '../../css/u/u3cz6_v6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="e8hb2u8yg"/><path class="yd2z58hmr"/><path class="gv0c9mbvs"/><path class="u3cz6_v6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:shaking-face" /></template>
