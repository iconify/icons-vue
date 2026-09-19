<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mucm1fdxh.css';
import '../../css/c/c6dys3_cr.css';
import '../../css/r/rrexukl6y.css';
import '../../css/p/pw7tkgboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mucm1fdxh"/><path class="c6dys3_cr"/><path clip-rule="evenodd" class="rrexukl6y"/><path class="pw7tkgboe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:miner-worker" /></template>
