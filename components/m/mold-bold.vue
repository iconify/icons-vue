<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eb_z5qbdz.css';
import '../../css/u/uc3w6cwkm.css';
import '../../css/l/lumasop3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eb_z5qbdz"/><path clip-rule="evenodd" class="uc3w6cwkm"/><path class="lumasop3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mold-bold" /></template>
