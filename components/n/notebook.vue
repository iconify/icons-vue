<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lcttltb3x.css';
import '../../css/x/x_cl_fbwy.css';
import '../../css/c/ccyq18bpb.css';
import '../../css/r/rlvqv6btf.css';
import '../../css/y/yw8zjyc1i.css';
import '../../css/o/o5e6ye6gk.css';
import '../../css/c/c6dpl4bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="lcttltb3x"/><path class="x_cl_fbwy"/><path class="ccyq18bpb"/><path class="rlvqv6btf"/><path class="yw8zjyc1i"/><path class="o5e6ye6gk"/><path class="c6dpl4bdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:notebook" /></template>
