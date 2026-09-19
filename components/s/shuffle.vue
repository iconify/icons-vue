<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/ttixfbczm.css';
import '../../css/u/u2kk0nupc.css';
import '../../css/x/xd4v8uixa.css';
import '../../css/y/y8meh6e1m.css';
import '../../css/i/iqg723bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ttixfbczm"/><path class="u2kk0nupc"/><path class="xd4v8uixa"/><path class="y8meh6e1m"/><path class="iqg723bwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:shuffle" /></template>
