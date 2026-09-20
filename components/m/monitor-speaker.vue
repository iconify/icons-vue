<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/yc2e94s8x.css';
import '../../css/k/koc_erasu.css';
import '../../css/p/pr_sh2lqz.css';
import '../../css/u/uxwj_xb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yc2e94s8x"/><rect class="koc_erasu"/><path class="pr_sh2lqz"/><circle class="uxwj_xb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:monitor-speaker" /></template>
