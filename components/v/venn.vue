<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ehp-zsmgk.css';
import '../../css/k/kgb4k9beb.css';
import '../../css/o/o0lxulbvo.css';
import '../../css/i/iwtfx8bgl.css';
import '../../css/q/qn9vpab8l.css';
import '../../css/f/f1v2nbs_m.css';
import '../../css/q/qnbgnf7_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ehp-zsmgk"/><path class="kgb4k9beb"/><path class="o0lxulbvo"/><path class="iwtfx8bgl"/><path class="qn9vpab8l"/><path class="f1v2nbs_m"/><path class="qnbgnf7_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:venn" /></template>
