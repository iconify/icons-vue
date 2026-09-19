<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fp00jbqxq.css';
import '../../css/c/cxsu3gbwu.css';
import '../../css/d/dpcidl-rd.css';
import '../../css/p/pm_m9qbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fp00jbqxq"/><path class="cxsu3gbwu"/><path clip-rule="evenodd" class="dpcidl-rd"/><path class="pm_m9qbfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:octagon" /></template>
