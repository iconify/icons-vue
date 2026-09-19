<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cxlyk5b-t.css';
import '../../css/x/xpxxzjbvo.css';
import '../../css/r/rt4x1ab2l.css';
import '../../css/y/yh2q36bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cxlyk5b-t"/><path class="xpxxzjbvo"/><path class="rt4x1ab2l"/><path class="yh2q36bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:palm-tree" /></template>
