<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/v/vmoz48bls.css';
import '../../css/q/qa2gjibfg.css';
import '../../css/x/xltar9lyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="vmoz48bls"/><ellipse transform="rotate(-90 10 16)" class="qa2gjibfg"/><path class="xltar9lyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:users-group" /></template>
