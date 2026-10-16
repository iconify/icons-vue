<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bstt3tdqg.css';
import '../../css/f/fva0wsn1j.css';
import '../../css/h/hgv2l4uaq.css';
import '../../css/q/qusq3nbol.css';
import '../../css/w/wvwyv9bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bstt3tdqg"/><path class="fva0wsn1j"/><path class="hgv2l4uaq"/><path class="qusq3nbol"/><path class="wvwyv9bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wetland-20-bold" /></template>
