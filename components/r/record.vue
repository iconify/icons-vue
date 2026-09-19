<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/i/ilsyr1bsh.css';
import '../../css/w/w98viukhh.css';
import '../../css/u/u1p5lybcx.css';
import '../../css/q/q3xq_00jy.css';
import '../../css/b/bu85uobwx.css';
import '../../css/f/fa3gi85sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="ilsyr1bsh"/><path class="w98viukhh"/><path class="u1p5lybcx"/><path class="q3xq_00jy"/><path class="bu85uobwx"/><path class="fa3gi85sj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:record" /></template>
