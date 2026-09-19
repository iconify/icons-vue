<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lao2y7iei.css';
import '../../css/k/k10jtebwe.css';
import '../../css/q/qkcequqdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lao2y7iei"/><path class="k10jtebwe"/><path class="qkcequqdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:smoke" /></template>
