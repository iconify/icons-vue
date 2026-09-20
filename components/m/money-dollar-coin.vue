<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/o/oh8elkb4f.css';
import '../../css/w/wvwbcz5yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="oh8elkb4f"/><path class="wvwbcz5yh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:money-dollar-coin" /></template>
