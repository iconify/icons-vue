<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/e/e-ud32bnc.css';
import '../../css/f/fxlk_dbbi.css';
import '../../css/f/fg1o3-nyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="e-ud32bnc"/><circle class="fxlk_dbbi"/><path class="fg1o3-nyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:music" /></template>
