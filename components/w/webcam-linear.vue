<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v_cyp7bey.css';
import '../../css/k/kva043bzk.css';
import '../../css/t/t26d7g3rg.css';
import '../../css/h/h16-ldbyu.css';
import '../../css/r/rtrl0bc1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v_cyp7bey"/><path class="kva043bzk"/><path class="t26d7g3rg"/><path class="h16-ldbyu"/><path class="rtrl0bc1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-linear" /></template>
