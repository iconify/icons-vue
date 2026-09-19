<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj66k2bbx.css';
import '../../css/w/wtfmx7b3v.css';
import '../../css/y/y7n_q-bpf.css';
import '../../css/f/f3bu0o9cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj66k2bbx"/><g class="wtfmx7b3v"><path class="y7n_q-bpf"/><path class="f3bu0o9cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:negative-dynamic" /></template>
