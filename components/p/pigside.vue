<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgdr4lbfa.css';
import '../../css/f/fi1ziub-o.css';
import '../../css/v/vex_8bfwg.css';
import '../../css/b/bsud8lbir.css';
import '../../css/x/x4ktgp36j.css';
import '../../css/v/v-xeifvgl.css';
import '../../css/o/og18_xuif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgdr4lbfa"/><path class="fi1ziub-o"/><path class="vex_8bfwg"/><path class="bsud8lbir"/><path class="x4ktgp36j"/><path class="v-xeifvgl"/><path class="og18_xuif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pigside" /></template>
