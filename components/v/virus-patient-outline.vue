<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a1818y12w.css';
import '../../css/z/zbf4nfbmn.css';
import '../../css/x/xjv1tcbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a1818y12w"/><path class="zbf4nfbmn"/><path clip-rule="evenodd" class="xjv1tcbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-patient-outline" /></template>
