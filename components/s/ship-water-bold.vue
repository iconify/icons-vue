<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b1c000c5t.css';
import '../../css/c/cecui5bdg.css';
import '../../css/q/qxy675oxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="b1c000c5t"/><path class="cecui5bdg"/><path class="qxy675oxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ship-water-bold" /></template>
