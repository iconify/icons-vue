<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsw5so5pt.css';
import '../../css/t/tm3avkrlq.css';
import '../../css/g/g5s0ynieo.css';
import '../../css/k/ks7wf3l0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsw5so5pt"/><circle class="tm3avkrlq"/><path class="g5s0ynieo"/><path class="ks7wf3l0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:picture" /></template>
