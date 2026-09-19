<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgxn76bkp.css';
import '../../css/e/e22nqiizq.css';
import '../../css/h/hkb-iz_va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="wgxn76bkp"><circle class="e22nqiizq"/><path class="hkb-iz_va"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:react-wordmark" /></template>
