<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sxx9kbcui.css';
import '../../css/u/u-7u5koqq.css';
import '../../css/d/dt7mfmbea.css';
import '../../css/y/y0t2_6s_t.css';
import '../../css/q/qnx9txbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="sxx9kbcui"/><path clip-rule="evenodd" class="u-7u5koqq"/><path class="dt7mfmbea"/><path class="y0t2_6s_t"/><path class="qnx9txbsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:poker" /></template>
