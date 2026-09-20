<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hq-5njbjh.css';
import '../../css/x/xfy0nnwjl.css';
import '../../css/f/fhy922bbx.css';
import '../../css/w/whvwt4bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hq-5njbjh"/><path class="xfy0nnwjl"/><path class="fhy922bbx"/><path class="whvwt4bny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-lines-broken" /></template>
