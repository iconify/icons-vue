<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uce-bntae.css';
import '../../css/m/moip_4bnz.css';
import '../../css/f/fkcgkpbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="uce-bntae"/><path clip-rule="evenodd" class="moip_4bnz"/><path class="fkcgkpbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:outpatient" /></template>
