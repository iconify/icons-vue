<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/g/g4x10rber.css';
import '../../css/w/wzh204bze.css';
import '../../css/u/u3ijsnwem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="g4x10rber"/><path class="wzh204bze"/><path class="u3ijsnwem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:wallet-money" /></template>
