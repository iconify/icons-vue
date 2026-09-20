<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi015tbty.css';
import '../../css/u/u50yvab1y.css';
import '../../css/e/erii6lbpv.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/u/usozxnbrm.css';
import '../../css/u/ulqv-3scp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xi015tbty"/><circle class="u50yvab1y"/><path class="erii6lbpv"/><g class="jn8qy4bru"><circle class="usozxnbrm"/><path class="ulqv-3scp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:waxing-crescent-moon" /></template>
