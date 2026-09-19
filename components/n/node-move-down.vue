<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nf8asibfv.css';
import '../../css/v/v_u7lbc8p.css';
import '../../css/i/iqbu_qwxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nf8asibfv"/><path class="v_u7lbc8p"/><path class="iqbu_qwxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:node-move-down" /></template>
