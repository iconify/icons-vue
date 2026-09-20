<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e2l1hx5yc.css';
import '../../css/m/m0sfndbwm.css';
import '../../css/n/ndcdy4d6d.css';
import '../../css/z/zvfketbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e2l1hx5yc"/><path class="m0sfndbwm"/><path class="ndcdy4d6d"/><path class="zvfketbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plug-circle-broken" /></template>
