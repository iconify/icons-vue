<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nnp4uwb7x.css';
import '../../css/m/mtnsjzhxu.css';
import '../../css/k/kc7tjn8cw.css';
import '../../css/i/im8k1r0vl.css';
import '../../css/z/zqvw3abzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nnp4uwb7x"/><path clip-rule="evenodd" class="mtnsjzhxu"/><path clip-rule="evenodd" class="kc7tjn8cw"/><path class="im8k1r0vl"/><path clip-rule="evenodd" class="zqvw3abzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:toilet-paper2x-outline" /></template>
