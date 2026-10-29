<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i87ljq8sy.css';
import '../../css/s/srigqbf1b.css';
import '../../css/w/w0rbxob2c.css';
import '../../css/q/qpd30mb9y.css';
import '../../css/p/pja5r2bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i87ljq8sy"/><path class="srigqbf1b wm-k"/><path class="w0rbxob2c wm-k"/><path class="qpd30mb9y wm-s"/><path class="pja5r2bbc wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-plus-sketch" /></template>
