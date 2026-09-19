<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u2f5qo9ra.css';
import '../../css/n/n-88vfcwe.css';
import '../../css/h/hphoz6f5k.css';
import '../../css/r/rgq2tbmxq.css';
import '../../css/k/kinyf4bfq.css';
import '../../css/u/umz_u252p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="u2f5qo9ra"/><path class="n-88vfcwe"/><path class="hphoz6f5k"/><circle class="rgq2tbmxq"/><path class="kinyf4bfq"/><path class="umz_u252p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:satellite-dish" /></template>
