<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxhnq1bnf.css';
import '../../css/r/rx2al_b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxhnq1bnf"/><path class="rx2al_b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-bank-20" /></template>
