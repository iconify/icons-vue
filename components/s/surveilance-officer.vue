<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s2sjd_bal.css';
import '../../css/l/lk154dd3j.css';
import '../../css/z/zj5fc_biz.css';
import '../../css/o/ordcnwbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s2sjd_bal"/><path class="lk154dd3j"/><path class="zj5fc_biz"/><path clip-rule="evenodd" class="ordcnwbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:surveilance-officer" /></template>
