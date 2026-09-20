<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj_bjbbzz.css';
import '../../css/q/q6z_ngbhj.css';
import '../../css/o/o57fo9bqu.css';
import '../../css/z/z04drlb1l.css';
import '../../css/k/kbyccgbdg.css';
import '../../css/h/h22dv30tg.css';
import '../../css/j/jk8vg9_ca.css';
import '../../css/j/jdcr3_b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nj_bjbbzz"/><path class="q6z_ngbhj"/><path class="o57fo9bqu"/><g class="z04drlb1l"><path class="kbyccgbdg"/><path class="h22dv30tg"/><path class="jk8vg9_ca"/><path class="jdcr3_b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:tsunami" /></template>
