<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s1by6sb-u.css';
import '../../css/h/hcu_kfy7h.css';
import '../../css/o/opmk2-vlj.css';
import '../../css/q/qzs_3vcvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="s1by6sb-u"/><path class="hcu_kfy7h"/><path class="opmk2-vlj"/><path class="qzs_3vcvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:walking-duo" /></template>
