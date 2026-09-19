<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n4adrdbbc.css';
import '../../css/w/wpr94kbcg.css';
import '../../css/o/o278vf_zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="n4adrdbbc"/><path class="wpr94kbcg"/><path class="o278vf_zl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:mobile-1" /></template>
