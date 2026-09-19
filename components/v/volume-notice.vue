<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/g/gnu-tacti.css';
import '../../css/f/fxm53-wkn.css';
import '../../css/a/a9mxpshxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="gnu-tacti"/><path class="fxm53-wkn"/><path class="a9mxpshxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:volume-notice" /></template>
