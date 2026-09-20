<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzbh_urec.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/p/p28c7-b8k.css';
import '../../css/x/xdloo4m_h.css';
import '../../css/j/ju8xeiqzy.css';
import '../../css/k/kpzn3ybxl.css';
import '../../css/s/sqvb8-iqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qzbh_urec"/><g class="brzn_0bpr"><path class="p28c7-b8k"/><path class="xdloo4m_h"/><circle class="ju8xeiqzy"/><circle class="kpzn3ybxl"/><path class="sqvb8-iqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:stretcher" /></template>
