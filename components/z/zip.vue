<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zxioyss3z.css';
import '../../css/j/jgkcneb9x.css';
import '../../css/p/pd8e-bc_k.css';
import '../../css/k/krp3398zx.css';
import '../../css/j/jtnjq2ijf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="zxioyss3z"/><path class="jgkcneb9x"/><path clip-rule="evenodd" class="pd8e-bc_k"/><path class="krp3398zx"/><path class="jtnjq2ijf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:zip" /></template>
