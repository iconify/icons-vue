<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/q/qx1rt3bor.css';
import '../../css/l/l477l9bhb.css';
import '../../css/y/ybktkkb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path clip-rule="evenodd" class="qx1rt3bor"/><path class="l477l9bhb"/><path class="ybktkkb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:sperm" /></template>
