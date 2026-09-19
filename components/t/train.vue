<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wolh3pfgd.css';
import '../../css/d/dn9gys-yh.css';
import '../../css/q/qwat3dvlt.css';
import '../../css/d/dxejs_bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wolh3pfgd"/><path clip-rule="evenodd" class="dn9gys-yh"/><path class="qwat3dvlt"/><rect class="dxejs_bvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:train" /></template>
