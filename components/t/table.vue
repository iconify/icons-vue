<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/l/ltjm4ubuf.css';
import '../../css/w/we1o4actj.css';
import '../../css/p/pp76qbckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="ltjm4ubuf"/><path class="we1o4actj wm-shine"/><path class="pp76qbckp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:table" /></template>
